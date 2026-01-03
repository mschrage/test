# Knock CLI Tool

Knock is a command-line tool that converts Adobe Content Server Message (ACSM) files into DRM-free EPUB ebooks on Linux systems.

## About

This software does not utilize Adobe Digital Editions nor Wine. It is completely free and open-source software written natively for Linux.

## Installation

The knock binary is located in `bin/knock` and is ready to use.

## Usage

```bash
./bin/knock ~/path/to/my-book.acsm
```

When you run knock for the first time, you will be prompted to enter your Adobe account email and password to register the device with Adobe.

## Requirements

- A free Adobe account (create at [account.adobe.com](https://account.adobe.com))
- Runtime dependencies: libcurl, libopenssl, and zlib (usually pre-installed on most Linux systems)

## Verified Book Sources

Knock should work on any ACSM file, but it has been specifically verified to work on ACSM EPUB files from:

- eBooks.com
- Rakuten Kobo
- Google Books
- Hugendubel.de (German)

## Source

This build was created using the knock-cmake project, which provides CMake-based compilation for the original knock tool.

- Original knock repository (offline): https://github.com/BentonEdmondson/knock
- knock-cmake: https://github.com/Alvin-He/knock-cmake
- Active forks: https://github.com/esn/knock, https://github.com/richard-kiss/knock

## License

This software is licensed under GPLv3.
