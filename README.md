# EXIF Fetcher: Image Metadata Extraction Tool

## Overview

EXIF Fetcher is a Python tool designed for extracting and analyzing EXIF metadata from images found on web pages. This tool helps in identifying images with GPS metadata, potentially revealing the location where the photos were taken. It's an invaluable resource for digital forensics investigations and privacy assessments.

## Installation

### Prerequisites

- Python 3.x
- BeautifulSoup4
- Pillow (PIL Fork)

Ensure Python is installed on your system. You can download Python from the [official website](https://www.python.org/downloads/).

### Libraries Installation

After installing Python, you can install the required libraries using pip:

```sh
pip install beautifulsoup4 pillow
```

## Usage

The tool takes a single command-line argument: the target URL to scan for images. Here's how to use it:

1. **Navigating to the Tool's Directory**: Open a terminal or command prompt and navigate to the directory where `exif_fetch.py` is located.

2. **Running the Tool**: Execute the script by passing the target URL as an argument:

   ```sh
   python3 exif_fetch.py <TARGET_URL>
   ```

   Replace `<TARGET_URL>` with the actual URL you want to analyze.

### Example

```sh
python3 exif_fetch.py https://example.com
```

This command scans for images on "https://example.com", downloads them, and checks for EXIF data including GPS metadata.

## Features

- **Image Discovery**: Finds all images embedded in a webpage.
- **Image Downloading**: Automatically downloads discovered images for local analysis.
- **EXIF Data Extraction**: Examines downloaded images for EXIF metadata, such as camera model, date taken, and potentially GPS coordinates.


## Disclaimer

Use EXIF Fetcher ethically and responsibly. Ensure you have permission to analyze images from the target website to avoid privacy violations or unauthorized data collection.

This README provides a basic guide to installing and using the EXIF Fetcher tool. It's essential to comply with all applicable laws and website policies when using this tool.
