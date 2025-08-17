# Moving Box Organizer - Local Installation

A complete moving box organization tool that runs entirely in your web browser with local data storage.

## Features

✅ **Create unlimited boxes** with custom names  
✅ **Sub-groups within boxes** for better organization (e.g., "Clothes", "Electronics")  
✅ **Add items with quantities** to boxes and sub-groups  
✅ **Edit everything** - box names, sub-group names, item names, and quantities  
✅ **Collapsible sub-groups** with folder icons for clean organization  
✅ **CSV export & import** for complete inventory management  
✅ **Smart search & filtering** across all boxes, groups, and items  
✅ **Dark mode** with persistent theme preference  
✅ **Keyboard shortcuts** for power users  
✅ **Drag & drop** items between boxes and sub-groups  
✅ **Bulk operations** - select and manage multiple items at once  
✅ **Local data storage** - your data is saved in your browser and never leaves your computer  
✅ **Works offline** - no internet connection required after initial setup  
✅ **Responsive design** - works on desktop, tablet, and mobile  

## Quick Start

### Option 1: Simple Setup (Recommended)
1. Download the `index.html` file to your computer
2. Double-click the file to open it in your web browser
3. Start organizing your boxes!

### Option 2: Local Web Server (For Advanced Users)
If you prefer to run it as a local web server:

1. **Using Python** (if you have Python installed):
   ```bash
   # Navigate to the folder containing index.html
   cd /path/to/moving-box-organizer-local
   
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Then open: http://localhost:8000
   ```

2. **Using Node.js** (if you have Node.js installed):
   ```bash
   # Install a simple server globally
   npm install -g http-server
   
   # Navigate to the folder and start server
   cd /path/to/moving-box-organizer-local
   http-server
   
   # Then open: http://localhost:8080
   ```

## How to Use

### Creating Boxes
1. Enter a box name (e.g., "Kitchen Items", "Bedroom Clothes")
2. Click "Create Box" or press **Ctrl+N**

### Adding Sub-Groups
1. In any box, click "Add Sub-Group"
2. Enter a sub-group name (e.g., "Clothes", "Electronics", "Books")
3. Click the + button to create it

### Adding Items
- **To a sub-group**: Use "Add item to this group..." within any sub-group
- **Directly to box**: Use "Add item directly to box..." at the bottom of each box
- Set quantities using the +/- buttons before adding items

### Managing Items
- **Edit names**: Click the pencil icon next to any box, sub-group, or item
- **Adjust quantities**: Use the +/- buttons next to items
- **Delete items**: Click the X button
- **Collapse/expand sub-groups**: Click on the sub-group header

### Search & Filter
- **Search**: Type in the search box to find specific items, boxes, or sub-groups
- **Sort**: Choose from Name (A-Z), Date Created, or Most Items
- **Real-time filtering**: Results update as you type

### Drag & Drop
- **Move items**: Click and drag items between boxes and sub-groups
- **Visual feedback**: See where items can be dropped
- **Automatic organization**: Items are moved instantly

### Bulk Operations
1. Click **"Bulk Mode"** to enable bulk selection
2. **Check items** you want to select
3. Use **bulk actions**:
   - **Select All**: Choose all items
   - **Clear**: Deselect all items
   - **Delete Selected**: Remove multiple items at once

### Import/Export Data
- **Export CSV**: Click "Export CSV" to download your complete inventory
- **Import CSV**: Click "Import CSV" to restore data from a previous export
- **Format**: CSV includes Box Name, Sub-Group, Item Name, Quantity, Date Added

### Dark Mode
- **Toggle**: Click the moon/sun icon in the header
- **Persistent**: Your preference is saved automatically
- **Smooth transitions**: Beautiful theme switching

### Keyboard Shortcuts
- **Ctrl+N**: Create new box
- **Ctrl+F**: Focus search
- **Ctrl+S**: Export CSV
- **Escape**: Clear search or close modals
- **?**: Show keyboard shortcuts
- **Click outside**: Close modals

## Data Storage

- **All data is stored locally** in your browser's localStorage
- **Your data never leaves your computer** - completely private
- **Data persists** between browser sessions
- **Works offline** after the initial page load
- **Theme preference** is also saved locally

## Example Organization Structure

```
📦 Kitchen Items (Box)
  📁 Appliances (Sub-group)
    • Coffee maker (x1)
    • Blender (x1)
    • Toaster (x1)
  📁 Dishes (Sub-group)
    • Dinner plates (x8)
    • Bowls (x6)
    • Cups (x4)
  • Kitchen towels (x5) [Direct in box]

📦 Bedroom Items (Box)
  📁 Clothes (Sub-group)
    • T-shirts (x10)
    • Jeans (x3)
    • Socks (x15)
  📁 Electronics (Sub-group)
    • Phone charger (x1)
    • Laptop (x1)
  • Pillow (x2) [Direct in box]
  • Blanket (x1) [Direct in box]
```

## Browser Compatibility

Works in all modern web browsers:
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Troubleshooting

**Q: My data disappeared!**  
A: Data is stored in your browser's localStorage. If you cleared your browser data or used incognito/private mode, the data will be lost. Always export to CSV for backup.

**Q: Can I use this on multiple devices?**  
A: Each device stores data independently. Use the CSV export/import feature to transfer data between devices.

**Q: The page won't load properly**  
A: Make sure you have an internet connection for the initial load (to download React and icons). After that, it works offline.

**Q: Can I customize the appearance?**  
A: Yes! The CSS is included in the HTML file. You can modify the styles to match your preferences.

**Q: How do I move items between boxes?**  
A: Click and drag items to move them between boxes and sub-groups. The cursor will change to a grab icon when hovering over draggable items.

**Q: How do I select multiple items?**  
A: Click "Bulk Mode" to enable bulk selection, then check the boxes next to items you want to select.

## Tips for Moving

1. **Start early** - Begin cataloging items weeks before your move
2. **Be specific** - Instead of "clothes", use "winter clothes", "work shirts", etc.
3. **Use quantities** - Knowing you have 15 books vs "some books" helps with planning
4. **Export regularly** - Create CSV backups as you add items
5. **Use search** - Quickly find items when you have many boxes
6. **Organize with sub-groups** - Keep related items together
7. **Use bulk operations** - Select multiple items for quick management
8. **Take photos** - While organizing digitally, photos of packed boxes can be helpful too

## Support

This is a standalone application that runs entirely in your browser. All data is stored locally on your device for complete privacy and offline functionality.

Enjoy your organized move! 📦✨

