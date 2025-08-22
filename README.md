# Brave Bookmarks Editor

A simple, web-based tool to edit and organize your Brave browser bookmarks with an intuitive interface and built-in safety features.

## Features

- 📁 **Visual Bookmark Management**: View bookmarks in a hierarchical tree structure
- ✏️ **Edit Bookmarks**: Rename bookmark titles and modify URLs
- 🗑️ **Delete Bookmarks**: Remove unwanted bookmarks with confirmation
- 🔗 **Open Links**: Open bookmarks in normal or private mode
- 📊 **Statistics**: View total bookmarks, folders, and links count
- 💾 **Export Options**: Download edited bookmarks in JSON or HTML format
- 🧪 **Testing Mode**: Safe environment for experimenting with bookmark changes
- ⚠️ **Backup Detection**: Warns about Brave's automatic bookmark restoration
- 📱 **Responsive Design**: Works on desktop and mobile devices

## Safety Features

### 🚨 Brave Auto-Backup Warning
The editor automatically detects when you load bookmarks and warns you about Brave's built-in backup and sync features that may restore deleted bookmarks. This helps you understand potential interference with your editing.

### 🧪 Testing Mode
- **Safe Experimentation**: Enable testing mode for risk-free bookmark editing
- **Automatic Backup**: Creates and downloads a backup file when activated
- **Visual Indicators**: Clear indication when testing mode is active
- **Enhanced Confirmations**: Different delete confirmations for testing vs. normal mode

## How to Use

### 1. Export Your Bookmarks from Brave
1. Open Brave browser
2. Navigate to: `C:\Users\[USERNAME]\AppData\Local\BraveSoftware\Brave-Browser\User Data\Default\`
3. Copy the `Bookmarks` file to your desktop
4. Rename it to `Bookmarks.json`

### 2. Edit Your Bookmarks
1. Open `index.html` in your web browser
2. Click "Choose File" and select your `Bookmarks.json` file
3. **Review the backup warning** that appears automatically
4. Choose to either:
   - Dismiss the warning if you understand the risks
   - Enable **Testing Mode** for safe experimentation
5. Edit bookmark names and URLs as needed
6. Delete unwanted bookmarks
7. Use the search function to find specific bookmarks

### 3. Export Your Changes
1. Click the "Export ▼" dropdown button
2. Choose your preferred format:
   - **📄 Export as JSON**: Brave-compatible format for importing back
   - **🌐 Export as HTML**: Standalone webpage for viewing/sharing

### 4. Import Back to Brave (JSON Export Only)
1. Close Brave browser completely
2. Navigate back to: `C:\Users\[USERNAME]\AppData\Local\BraveSoftware\Brave-Browser\User Data\Default\`
3. **Backup original**: Rename existing `Bookmarks` to `Bookmarks.backup`
4. Copy your exported JSON file to this location
5. Rename exported file from `brave-bookmarks-edited-[date].json` to `Bookmarks`
6. Restart Brave

## Installation

### Option 1: Download and Run Locally
1. Download `index.html`
2. Open it in any modern web browser
3. No installation required!

### Option 2: GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Access via: `https://[username].github.io/brave-bookmarks-editor`

## Browser Compatibility

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Brave

## Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies
- **Client-side only** - Your bookmarks never leave your device
- **Responsive design** - Works on all screen sizes
- **Drag & drop support** - Easy file uploading
- **Automatic backup creation** - Safety-first approach
- **Dual export formats** - JSON for importing, HTML for viewing

## Security

- All processing happens locally in your browser
- No data is sent to any server
- Your bookmarks remain private and secure
- Automatic backup creation in testing mode
- Clear warnings about potential data restoration

## Understanding Brave's Backup Behavior

### Why Bookmarks Might Be Restored
Brave browser has several mechanisms that can restore deleted bookmarks:

1. **Brave Sync**: If enabled, deleted bookmarks may be restored from other synced devices
2. **Local Backups**: Brave creates automatic local backups that may restore changes
3. **Session Restoration**: Browser restart might restore previous bookmark state

### Recommended Testing Approach
1. **Use Testing Mode**: Enable the built-in testing mode for safe experimentation
2. **Disable Brave Sync**: Turn off sync in Brave settings before major edits
3. **Work with Exported Files**: Use exported JSON files for testing instead of live browser data
4. **Create Manual Backups**: Always backup your original bookmarks file

## Future Development Ideas

### Additional Brave Browser Files
The editor could potentially be expanded to manage other Brave browser data:

- **Login Data** (`Login Data`): Saved passwords and login information
- **History** (`History`): Browsing history database
- **Extensions** (`Extensions/` folder): Installed extension data
- **Preferences** (`Preferences`): Browser settings and configurations
- **Sessions** (`Current Session`, `Last Session`): Tab and window states
- **Cookies** (`Cookies`): Website cookies and site data

### Potential Future Features
- **Brave Data Manager**: Comprehensive tool for all Brave browser data
- **History Viewer**: Browse and search through browsing history
- **Extension Manager**: Backup and restore extension configurations
- **Settings Backup**: Export and import browser preferences
- **Sync Status Monitor**: Real-time sync status and conflict resolution

**Security Note**: Future features involving sensitive data like passwords would require additional security measures and user consent.

## Contributing

Feel free to submit issues and pull requests!

## License

MIT License - Feel free to use and modify as needed.

---

**Important**: Always backup your original bookmarks file before making changes! Use Testing Mode for safe experimentation.