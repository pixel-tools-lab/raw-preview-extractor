# RAW Preview Extractor

![Version](https://img.shields.io/badge/version-v1.0_(Build_0.38)-blue.svg)
![License](https://img.shields.io/badge/license-Freeware-green.svg)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)

**RAW Preview Extractor** is a high-performance, multithreaded Windows utility developed by **Pixel Tools Lab**. Designed for photographers, it rapidly extracts embedded JPEG previews and converts RAW images using ExifTool and ImageMagick, completely bypassing the slow import times of standard photo editors.

*Note: This repository hosts the official documentation, issue tracker, and release binaries for the software. The source code is closed and proprietary.*

## 📥 Download & Installation

1. Navigate to the **[Releases](../../releases/latest)** page on the right side of this repository.
2. Download the `RAW-Preview-Extractor-Setup.exe` file under "Assets".
3. Run the installer. It will automatically handle dependencies and create a Start Menu shortcut.

## 📖 Help & Usage Guide

Using the software is straightforward:

1. **Source:** Choose a directory containing your RAW files or select a single image.
2. **Destination:** Set where the converted JPEGs will be saved. (Defaults to a `JPEGs` subfolder).
3. **Quick Options:** Toggle Resizing, Watermarking, and EXIF Metadata retention directly from the main window.
4. **Preferences:** Click 'Preferences' to adjust CPU threads, customize your watermark (text, font, opacity, size, and position), set output resolution, and switch between Light/Dark themes.
5. **Start:** Click `Start Extraction` to begin. You can pause or safely cancel the operation at any time.

**Supported Formats:** `.cr2`, `.cr3`, `.nef`, `.arw`, `.dng`, `.raf`, `.orf`, `.rw2`, `.tif`, `.tiff`, `.psd`.

## ©️ Licensing & Credits

RAW Preview Extractor is provided as **Freeware**. You are free to use it for personal and commercial photography workflows. Redistribution, modification, or claiming ownership of this software is strictly prohibited. Please see the `LICENSE.txt` and `EULA.txt` files for full terms.

**Third-Party Dependencies:**
This software utilizes the incredible work of the following open-source projects:
* **[ExifTool](https://exiftool.org/)** by Phil Harvey
* **[ImageMagick](https://imagemagick.org/)** by ImageMagick Studio LLC
