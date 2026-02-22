<p align="center">
  <img src="logo.png" alt="QR Batch Generator Logo" width="120" height="120">
</p>

# QR Batch Generator

A simple and efficient web-based tool for generating QR codes individually or in batches from CSV files.

![QR Batch Generator](https://img.shields.io/badge/QR-Generator-purple) ![License](https://img.shields.io/badge/license-MIT-blue)

## Features

- **Single QR Code Generation**: Quickly generate QR codes for any text or URL
- **Batch Processing**: Upload a CSV file to generate multiple QR codes at once
- **Download Options**: Download individual QR codes or all codes as a ZIP file
- **Real-time Preview**: See your QR code instantly as you type
- **Drag & Drop Support**: Easily upload CSV files by dragging and dropping
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **No Server Required**: Runs entirely in the browser - no data is sent to any server

## Demo

Try the live demo at [milhaniq.github.io/qr-generator.com](https://milhaniq.github.io/qr-generator)

## Usage

### Single Mode

1. Click on the "Single Mode" tab
2. Enter your text or URL in the input field
3. Your QR code will be generated automatically
4. Click "Download QR Code" to save it as a PNG file

### Batch Mode

1. Click on the "Batch Mode" tab
2. Prepare a CSV file with two columns: `label` and `url`
3. Upload your CSV file by clicking or dragging it into the upload area
4. Preview all generated QR codes
5. Click "Download All as ZIP" to save all QR codes in a single ZIP file

#### CSV Format Example

```csv
label,url
Google,https://www.google.com
GitHub,https://www.github.com
Twitter,https://www.twitter.com
```

## Installation

Simply open the `index.html` file in any modern web browser. No installation or build process required.

For local development:

```bash
# Clone the repository
git clone https://github.com/yourusername/qr-batch-generator.git

# Navigate to the project directory
cd qr-batch-generator

# Open index.html in your browser
# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## Technologies Used

- **QRCode.js** - QR code generation library
- **JSZip** - ZIP file creation
- **FileSaver.js** - File saving functionality
- **Vanilla JavaScript** - No framework dependencies
- **CSS3** - Modern styling with gradients and animations

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

Made with ❤️ by [milhaniq.com](https://milhaniq.com)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

For issues, questions, or suggestions, please open an issue on GitHub.

---


