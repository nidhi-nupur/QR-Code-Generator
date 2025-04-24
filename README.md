# QR Code Generator

This is a simple Node.js application that generates a QR code from a user-provided URL and saves both the QR code image and the URL in local files.

## Features

- Prompts the user to enter a URL
- Generates a QR code image from the URL using the `qr-image` package
- Saves the QR code as `qr_img.png`
- Saves the URL as plain text in `URL.txt`

---

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- npm (Node Package Manager)

---

## Installation

1. **Clone the repository or download the source code.**

```bash
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator
```

2. **Install dependencies.**

```bash
npm install inquirer qr-image
```

---

## Usage

Run the application using Node:

```bash
node index.js
```

Follow the prompts:

- Paste your URL when asked
- Press `Enter`

The application will:

✅ Create a **QR code image** and save it as `qr_img.png`  
✅ Save the **entered URL** in a file named `URL.txt`

---

## Output Files

- `qr_img.png` → QR code image of the provided URL
- `URL.txt` → Contains the raw URL you entered

---

## Dependencies

- [`inquirer`](https://www.npmjs.com/package/inquirer) – For user input in the terminal
- [`qr-image`](https://www.npmjs.com/package/qr-image) – To generate QR code images
- Native Node.js `fs` module – For file operations

---

## Author

**Nidhi Nupur**  
Crafted with ❤️ using Node.js
