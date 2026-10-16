# Kayralrics No Trace — Photo Metadata Cleaner

A compact, privacy-focused photo metadata cleaner with a distinctive black-and-red interface.

## Run locally

1. Extract the ZIP archive.
2. Open `index.html` in a modern browser.
3. Select or drag in a supported image, choose **Remove metadata**, then download the cleaned file.

No build step, installation, server, account, analytics, or external API is required. Supported images are processed locally in the browser.

## Supported formats

- JPEG / JPG
- PNG
- WebP
- GIF

The cleaner removes known metadata and nonessential extension blocks while preserving image-coded data without re-encoding. Color profiles, animation control data, and orientation information may be preserved where needed for the image to continue displaying as intended. No tool can promise lossless metadata removal for every image format; HEIC, AVIF, TIFF, and camera RAW formats are not supported by this version.

## Security and privacy notes

- The page uses a restrictive Content Security Policy and does not connect to external services.
- Files are read and processed in the browser and are not uploaded.
- Use a current browser and keep a copy of important originals.
