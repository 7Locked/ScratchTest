# ScratchTest

A minimal test project for running the original Scratch 0.1 in your browser, powered by [SqueakJS](https://squeak.js.org/).

This project uses the [SqueakJS-embed-kit](https://github.com/NewGoogleDrive/SqueakJS-embed-kit/releases/tag/v1.0) for a lightweight, straightforward SqueakJS deployment—making it easy to experiment with legacy Scratch without extra files or complexity.

---

## ⚠️ About This Project

**This repository is made purely for testing purposes.**  
Its main purpose is to see if running Scratch 0.1 with SqueakJS works before porting the feature to my main website ([7Locked](https://github.com/7Locked/7locked.github.io)) in the near future.

---

## 🚀 Demo

[Run Scratch 0.1 in your browser](squeakjs/run/index.html#image=../images/Scratch11Oct03.image)

## Features

- Instantly launches the classic Scratch 0.1 environment in your browser
- Leverages SqueakJS-embed-kit for quick, minimal setup
- Minimal and fast-loading

## How It Works

- This repo embeds SqueakJS (via the SqueakJS-embed-kit) and loads the original Scratch 0.1 image file.
- Users can interact with the early Scratch interface directly in most modern browsers—no plugins required.

## Quick Start

1. Clone the repo:
    ```bash
    git clone https://github.com/7Locked/ScratchTest.git
    ```
2. Open `index.html` in your browser  
   *(For full functionality, run a simple local web server)*

    ```bash
    # Using Python 3.x
    python3 -m http.server
    # Then visit http://localhost:8000 in your browser
    ```

3. Click the **Run Scratch 0.1** button on the home page.

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- (Optional) Local web server for file loading support

## Project Structure

- `index.html` – Launch page, styled with Tailwind CSS
- `squeakjs/` – SqueakJS runtime (from SqueakJS-embed-kit)
- `images/` – Scratch 0.1 image file and supporting assets

## Credits

- **[SqueakJS](https://github.com/codefrau/SqueakJS)** — JavaScript Squeak/Smalltalk VM (MIT License)
- **[SqueakJS-embed-kit](https://github.com/NewGoogleDrive/SqueakJS-embed-kit)** — Lightweight repackaging for embedding SqueakJS
- **Scratch** — Early Scratch image by MIT Media Lab

## License

MIT License.  
See LICENSE for details. SqueakJS is MIT-licensed; SqueakJS-embed-kit is distributed for easy embedding—see its repo for details.

---

Enjoy experimenting with Scratch 0.1!
