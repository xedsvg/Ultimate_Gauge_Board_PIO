# Ultimate Gauge Board Web Installer

This folder contains the GitHub Pages site for easy firmware installation using ESP Web Tools.

## Browser Compatibility:
- ✅ **Supported:** Chrome, Edge, Opera, and other Chromium-based browsers
- ❌ **Not Supported:** Firefox, Safari (limited Web Serial API support)

## Files:
- `index.html` - The main web installer page with browser compatibility checks
- `manifest.json` - ESP Web Tools configuration file

## Setup:
1. Go to your repository Settings → Pages
2. Set Source to "Deploy from a branch"
3. Set Branch to "main" and folder to "/docs"
4. Save

Your web installer will be available at: `https://xedsvg.github.io/Ultimate_Gauge_Board_PIO/`

## How it works:
- Browser compatibility is automatically detected
- Users get clear warnings if their browser isn't supported
- ESP Web Tools downloads the latest firmware from GitHub Releases
- Firmware is flashed directly to the ESP32-S3 device
- No additional software installation required!