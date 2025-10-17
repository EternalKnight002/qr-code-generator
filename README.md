# Quick QR Code Generator

A lightweight Chrome extension that instantly generates QR codes for the current page URL or any custom text. Perfect for quickly sharing links across devices or with others.

![Extension Preview](https://img.shields.io/badge/version-1.0-blue.svg)
![Chrome Extension](https://img.shields.io/badge/platform-Chrome-green.svg)

## Features

- 🚀 **Instant QR Code Generation** - Automatically generates a QR code for the current tab's URL when opened
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
   - Click the extension icon in your toolbar
   - A QR code for the current page URL will be displayed automatically

2. **Generate QR for Custom Text**
   - Click the extension icon
   - Edit or replace the text in the input field
   - The QR code updates in real-time as you type

3. **Download QR Code**
   - Click the **Download QR Code** button
   - The QR code will be saved as `qrcode.png` in your downloads folder

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- QR Code generation powered by [davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs)
- Inspired by the need for quick and easy QR code sharing

## Support

If you encounter any issues or have suggestions, please [open an issue](https://github.com/EternalKnight002/qr-code-generator/issues) on GitHub.

---

Made with ❤️ for quick QR code generation
