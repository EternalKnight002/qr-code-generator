# Quick QR Code Generator

A lightweight Chrome extension that instantly generates QR codes for the current page URL or any custom text. Perfect for quickly sharing links across devices or with others.

![Extension Preview](https://img.shields.io/badge/version-1.1-blue.svg)
![Chrome Extension](https://img.shields.io/badge/platform-Chrome-green.svg)

## Features

- 🚀 **Instant QR Code Generation** - Automatically generates a QR code for the current tab's URL when opened
- ⌨️ **Keyboard Shortcut** - Press `Ctrl+Shift+Q` (or `Cmd+Shift+Q` on Mac) to open the extension instantly
- ⌨️ **Real-time Updates** - QR code updates instantly as you type custom text
- 💾 **Download Support** - Save QR codes as PNG images with a single click
- 🎨 **Clean Interface** - Simple, intuitive popup design
- ⚡ **Lightweight** - Minimal permissions required (only `activeTab`)

## Installation

### From Source

1. Clone this repository or download the ZIP file:
   ```bash
   git clone https://github.com/EternalKnight002/qr-code-generator.git
   ```

2. Open Chrome and navigate to `chrome://extensions/`

3. Enable **Developer mode** (toggle in the top-right corner)

4. Click **Load unpacked** and select the extension directory

5. The extension icon will appear in your Chrome toolbar

## Usage

1. **Generate QR for Current Page**
   - Click the extension icon in your toolbar, OR
   - Press `Ctrl+Shift+Q` (`Cmd+Shift+Q` on Mac) for quick access
   - A QR code for the current page URL will be displayed automatically

2. **Generate QR for Custom Text**
   - Open the extension (click icon or use keyboard shortcut)
   - Edit or replace the text in the input field
   - The QR code updates in real-time as you type

3. **Download QR Code**
   - Click the **Download QR Code** button
   - The QR code will be saved as `qrcode.png` in your downloads folder

4. **Customize Keyboard Shortcut** (Optional)
   - Navigate to `chrome://extensions/shortcuts`
   - Find "Quick QR Code Generator"
   - Click the edit icon to set your preferred shortcut

## File Structure

```
quick-qr-generator/
├── manifest.json          # Extension configuration
├── popup.html            # Extension popup interface
├── popup.css             # Styling for the popup
├── popup.js              # Main extension logic
├── qrcode.min.js         # QR code generation library
└── icons/
    ├── icon16.png        # 16x16 icon
    ├── icon48.png        # 48x48 icon
    └── icon128.png       # 128x128 icon
```

## Permissions

This extension requires minimal permissions:
- **activeTab** - To access the current tab's URL for QR code generation

## Technologies Used

- **Manifest V3** - Latest Chrome extension architecture
- **QRCode.js** - JavaScript library for QR code generation
- **Chrome Extensions API** - For browser integration
- **Commands API** - For keyboard shortcut support

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Ideas for Enhancement

- [ ] Color customization for QR codes
- [ ] Multiple size options
- [ ] History of generated QR codes
- [ ] Support for vCard, WiFi, and other QR code types
- [ ] Dark mode support
- [x] Keyboard shortcut support

## Changelog

### Version 1.1
- ✨ Added keyboard shortcut support (`Ctrl+Shift+Q` / `Cmd+Shift+Q`)
- 🎯 Power users can now open the extension without clicking

### Version 1.0
- 🎉 Initial release
- Basic QR code generation functionality
- Real-time text input updates
- Download QR codes as PNG

## License

This project is licensed under GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- QR Code generation powered by [davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs)
- Inspired by the need for quick and easy QR code sharing
- Keyboard shortcut feature suggested by [@0xcb198609](https://twitter.com/0xcb198609)

## Support

If you encounter any issues or have suggestions, please [open an issue](https://github.com/EternalKnight002/qr-code-generator/issues) on GitHub.

---

Made with ❤️ for quick QR code generation