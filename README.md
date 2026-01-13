# Teleprompter Web App

## Overview

A fully-featured, responsive teleprompter web application that runs directly in your browser. This tool helps presenters, speakers, and content creators read scripts smoothly during recordings, live streams, or presentations. The application works on desktop and mobile devices with an intuitive interface.

## Features

### 📝 Script Management
- Create, edit, and save multiple scripts
- Import text files (.txt, .md)
- Auto-save to browser storage
- Script preview and selection
- Delete functionality with confirmation

### 🎚️ Teleprompter Display
- Smooth, adjustable scrolling with speed control
- Progress bar to track reading position
- Basic Markdown formatting support (headers, bold, italic, code)
- Responsive display with customizable fonts and sizes
- Touch-friendly controls for mobile devices

### ⚙️ Customization
- Multiple font family options (Courier New, Arial, Times, etc.)
- Adjustable font size and line height
- Zoom controls for better readability
- Scroll speed control (0.1x to 2.0x)
- Settings persistence across sessions

### 🎮 Controls
- Start/Pause/Stop buttons
- Keyboard shortcuts for quick control
- Touch gestures for manual scrolling
- Direct navigation between Scripts and Teleprompter tabs

## Keyboard Shortcuts

- **Spacebar**: Start/Pause teleprompter
- **Escape**: Stop teleprompter
- **Ctrl+S (Cmd+S)**: Save script
- **Ctrl+1 (Cmd+1)**: Switch to Scripts tab
- **Ctrl+2 (Cmd+2)**: Switch to Teleprompter tab

## Mobile Support

- Touch gestures for manual scrolling
- Optimized interface for smaller screens
- Touch-friendly buttons and controls
- Prevent accidental zoom during use

## How to Use

### 1. Creating a Script
1. Click the **"New"** button in the Scripts tab
2. Type or paste your script in the editor
3. Use Markdown formatting for better readability
4. Click **"Save Changes"** to store the script

### 2. Loading a Script
1. Click **"Load File"** to import a text file
2. Or select an existing script from the sidebar
3. Scripts are automatically saved in your browser

### 3. Using the Teleprompter
1. Switch to the **Teleprompter** tab
2. Select a script if not already loaded
3. Adjust the scroll speed using the slider
4. Click **"Start"** to begin scrolling
5. Use **Pause** and **Stop** as needed

### 4. Customizing Display
- Change font type, size, and zoom in the Scripts tab
- Adjust line height for better readability
- Settings are saved automatically

## Technical Details

### Storage
- Uses `localStorage` for script persistence
- Settings saved between sessions
- No server-side storage (works offline after loading)

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome for Android)
- Requires JavaScript enabled

### File Support
- Text files (.txt)
- Markdown files (.md)
- Copy/paste from any text source

## Privacy

- All data stays in your browser
- No external data transmission
- No cookies or tracking

## Getting Started

Simply open the HTML file in any modern web browser. No installation required. The application works offline after the initial load.

## Tips for Best Results

1. Use clear formatting with headings and paragraphs
2. Test different scroll speeds to find your comfortable pace
3. Adjust font size for your viewing distance
4. Use the zoom feature for better readability
5. Practice with the Pause button to control the flow

## Troubleshooting

**Scripts not saving?**
- Check if your browser allows localStorage
- Try clearing browser cache and reloading

**Scrolling too fast/slow?**
- Adjust the speed slider in the Teleprompter tab
- Remember you can pause at any time

**Formatting not showing?**
- Use simple Markdown: `#` for headings, `**bold**`, `*italic*`

## License

This program is available under the Apache 2.0 license.
