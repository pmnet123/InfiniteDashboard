# Infinite Dashboard - Complete User Manual

An interactive, infinite canvas dashboard for creating and managing blocks with rich text, connections, and visual organization.

## Table of Contents
- [Getting Started](#getting-started)
- [Navigation & Zoom](#navigation--zoom)
- [Block Management](#block-management)
- [Text Editing](#text-editing)
- [Connections & Connectors](#connections--connectors)
- [Search Functionality](#search-functionality)
- [Customization](#customization)
- [Data Management](#data-management)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Advanced Features](#advanced-features)

---

## Getting Started

Open `infinite.html` in a modern web browser (Chrome, Edge, Firefox, or Safari). The dashboard loads with an infinite grid where you can create blocks, connect them, and organize your content.

---

## Navigation & Zoom

### Mouse Navigation
- **Pan/Drag**: Left-click and drag on empty space to move around the canvas
- **Zoom**: Use mouse wheel to zoom in/out at cursor position
- **Zoom Levels**: 20% minimum to 500% maximum

### Keyboard Navigation (NEW!)
- **Arrow Keys**: Navigate the canvas when not editing text or searching
  - **↑ Up Arrow**: Move up 20% of screen height
  - **↓ Down Arrow**: Move down 20% of screen height
  - **← Left Arrow**: Move left 20% of screen width
  - **→ Right Arrow**: Move right 20% of screen width

### Quick Zoom
- **Double Left-Click on Empty Space**: Zoom to 100% (1:1 scale)
- **Double Right-Click**: Zoom out to 20% overview
- **Z Key**: Reset zoom to 100%

### Visual Indicators
- **Scale Indicator**: Bottom-right corner shows current zoom percentage
- **Grid**: Visual grid lines help with alignment and positioning

---

## Block Management

### Creating Blocks
- **Right-Click on Empty Space** → Select "Add Colored Box"
- Blocks are created with random modern colors
- Default size: 150x100 pixels

### Moving Blocks
- **Left-Click and Drag**: Move blocks around the canvas
- Blocks can be positioned anywhere on the infinite canvas

### Resizing Blocks
- **Hover over Block Edges**: Cursor changes to resize cursor
- **Drag Edges**: Resize from right or bottom edges
- **Corner Resize**: Drag bottom-right corner to resize both dimensions
- **Minimum Size**: 20x20 pixels

### Block Actions (Right-Click on Block)
- **Change Color**: Pick a new color for the block
- **Copy Block**: Duplicate the block with same content and formatting
- **Delete Block**: Remove block and all its connections (with confirmation)

---

## Text Editing

### Basic Text Editing
- **Double Left-Click on Block**: Open rich text editor
- **Type**: Add and edit text content
- **Click Outside or Blur**: Save and close editor
- **Auto-Save**: Changes are automatically saved when editor closes

### Rich Text Formatting
- **Right-Click in Text Editor**: Open formatting menu
- **Select Text First**: Highlight text before applying formatting

#### Formatting Options
- **Bold (B)**: Make text bold
- **Italic (I)**: Make text italic  
- **Underline (U)**: Underline text
- **Font Family**: Choose from Arial, Times New Roman, Courier New, Helvetica, Georgia, Verdana
- **Font Size**: 8px to 32px options
- **Text Color**: Color picker for custom text colors

### URL Auto-Linking
- **Automatic Detection**: URLs are automatically converted to clickable links
- **Supported Formats**: 
  - `https://example.com`
  - `http://example.com`
  - `www.example.com`
  - `example.com`
- **Link Interaction**:
  - **Ctrl+Click**: Open link in new tab (while editing)
  - **Hover**: Show tooltip with link destination

---

## Connections & Connectors

### Creating Connections
1. **Right-Click on Empty Space** → Select "Add Connector"
2. **Click First Block**: Select source block
3. **Click Second Block**: Select target block
4. Connection is created automatically

### Connector Styles
- **Arrows**: Connectors show directional flow with arrow indicators
- **Gradient Colors**: Automatic gradient coloring that adapts to background
- **Smooth Lines**: Anti-aliased lines with rounded caps

### Connector Customization (Right-Click on Connector)
- **Toggle Arrows**: Show/hide directional arrows
- **Toggle Dashed**: Switch between solid and dashed lines
- **Delete Connector**: Remove the connection (with confirmation)

### Deleting Connections
**Method 1**: Right-click connector → "Delete Connector"
**Method 2**: 
1. Right-click empty space → "Delete Connector"
2. Click first connected block
3. Click second connected block
4. Connector between them is removed

---

## Search Functionality

### Opening Search
- **Ctrl+F**: Open search bar
- **Right-Click** → "Search": Alternative access method

### Search Features
- **Real-time Search**: Results update as you type
- **Text Content**: Searches both plain text and rich text content
- **Case Insensitive**: Matches regardless of case
- **Highlight Results**: Found blocks are highlighted with colored borders

### Search Navigation
- **Enter**: Go to next result
- **Shift+Enter**: Go to previous result
- **◀ ▶ Buttons**: Navigate between results
- **Counter**: Shows current result and total matches
- **Current Result**: Highlighted with animated pulsing border

### Closing Search
- **Escape Key**: Close search and clear highlights
- **X Button**: Close search interface

---

## Customization

### Background Color
- **Right-Click on Empty Space** → "Change Background Color"
- **Color Picker**: Choose any color for the canvas background
- **Adaptive Elements**: Grid, connectors, and shadows automatically adapt to background

### Block Colors
- **Right-Click on Block** → "Change Color"
- **Modern Color Palette**: Blocks are created with contemporary color schemes
- **Custom Colors**: Use color picker for precise color selection

### Visual Themes
- **Automatic Contrast**: Text and UI elements automatically adjust for readability
- **Glassmorphism**: UI elements use modern glass-like transparency effects
- **Shadows and Depth**: Blocks cast realistic shadows for depth perception

---

## Data Management

### Saving Your Work
- **Right-Click** → "Save" (or **Ctrl+S** in compatible browsers)
- **File Format**: JSON format with all data and positioning
- **Encryption Option**: Optional password protection for sensitive data
- **File Picker**: Modern browser file save dialog

### Loading Projects
- **Right-Click** → "Load"
- **File Selection**: Choose previously saved JSON files
- **Encryption Support**: Automatically detects and prompts for password
- **Complete Restoration**: Restores all blocks, connections, positioning, and zoom level

### Data Security
- **AES-256 Encryption**: Military-grade encryption when password is used
- **PBKDF2 Key Derivation**: 100,000 iterations for password security
- **Local Storage**: No data is sent to external servers

---

## Keyboard Shortcuts

### General Navigation
- **Arrow Keys**: Navigate canvas (20% screen movement)
- **Z**: Reset zoom to 100%
- **Ctrl+Z**: Undo last action
- **Escape**: Close search, context menus, or cancel operations

### Search
- **Ctrl+F**: Open search
- **Enter**: Next search result
- **Shift+Enter**: Previous search result
- **Escape**: Close search

### Text Editing
- **Double-Click Block**: Open text editor
- **Right-Click in Editor**: Open formatting menu
- **Ctrl+Click Link**: Open link in new tab (while editing)

---

## Advanced Features

### Undo System
- **10-Level History**: Maintains last 10 actions for undo
- **State Tracking**: Tracks blocks, connections, positioning, colors, and background
- **Smart Saves**: Only saves state when actual changes occur
- **Memory Efficient**: Automatically manages history size

### Link Management
- **Auto-Detection**: Automatically identifies and links URLs in text
- **Click Handling**: Smart link interaction during editing
- **Visual Styling**: Links are styled with blue color and underlines
- **Security**: Links open in new tabs with security attributes

### Performance Optimizations
- **Efficient Rendering**: Optimized canvas drawing for smooth performance
- **Hit Detection**: Fast algorithms for clicking and selecting elements
- **Memory Management**: Automatic cleanup of unused resources
- **Responsive Design**: Adapts to different screen sizes and resolutions

### Context-Aware UI
- **Dynamic Menus**: Context menus change based on what's clicked
- **Smart Highlighting**: Different highlight styles for search results
- **Adaptive Colors**: UI elements adapt to background colors for visibility
- **State Management**: Remembers current mode and prevents conflicts

---

## Browser Compatibility

### Fully Supported
- **Chrome/Chromium** (Latest)
- **Microsoft Edge** (Latest)
- **Safari** (Latest)
- **Firefox** (Latest)

### Required Features
- **Canvas API**: For drawing and rendering
- **File API**: For save/load functionality
- **Web Crypto API**: For encryption features
- **Modern JavaScript**: ES6+ features

---

## Tips & Tricks

### Productivity Tips
1. **Use Arrow Keys**: Quickly navigate large canvases
2. **Search First**: Use Ctrl+F to find blocks in complex diagrams
3. **Copy Blocks**: Duplicate similar blocks instead of creating from scratch
4. **Zoom Out**: Use double right-click for overview of entire canvas
5. **Group with Connectors**: Use connectors to show relationships and flow

### Organization Strategies
1. **Color Coding**: Use different colors for different types of content
2. **Hierarchical Layout**: Arrange blocks in tree or flow structures  
3. **Regular Saving**: Save frequently with descriptive filenames
4. **Version Control**: Save different versions of evolving projects

### Troubleshooting
- **Double-Click Not Working**: Try clicking more slowly or ensure clicks are close together
- **Text Not Saving**: Click outside the text editor to save changes
- **Search Not Finding**: Check spelling and remember search is case-insensitive
- **Performance Issues**: Try zooming out or reducing number of blocks visible

---

## Version History

### Latest Version Features
- ✅ Arrow key navigation (20% screen movement)
- ✅ Improved double-click reliability  
- ✅ Enhanced search functionality
- ✅ Undo system with 10-level history
- ✅ URL auto-linking in text
- ✅ Encryption support for saved files
- ✅ Modern glassmorphism UI design
- ✅ Adaptive color schemes
- ✅ Performance optimizations

---

*For technical support or feature requests, refer to the project documentation or contact the development team.*