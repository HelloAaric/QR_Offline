EN [English](README_en.md)

ZH_CN [中文](README.md)

# Advanced Offline QR Code Tool

A fully offline QR code generation and scanning tool that uses local libraries, requiring no internet connection. Note: Only supports the Chrome browser.

## Features

- Generate QR codes from text, URLs, or any content
- Customize QR code size, foreground color, and background color
- Download generated QR codes as PNG images
- Scan QR codes using the camera (requires camera permission)
- Copy scanned content with one click
- Open scanned URLs directly
- Smooth animations and responsive design

## How to Use

1. Clone this repository to your local machine
2. Open the `offline-qrcode-tool.html` file in Chrome browser
3. Use the "Generate QR Code" panel to create QR codes
4. Use the "Scan QR Code" panel to scan QR codes (allow camera access when prompted)

## Technical Details

- Uses [qrcode.min.js](https://davidshimjs.github.io/qrcodejs/) for QR code generation
- Uses [jsQR](https://github.com/cozmo/jsQR) for QR code scanning
- Pure front-end implementation, no backend required
- Works offline after downloading

## Screenshot

![image](https://github.com/user-attachments/assets/6229e0d6-8fcc-4df6-af41-003f90b76e6b)

## License

MIT License
