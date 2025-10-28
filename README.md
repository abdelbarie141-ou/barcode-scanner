# 🧾 Scan Reveal App (Barcode Reader with n8n)

A learning project that scans barcodes using a Lovable frontend and processes data through an n8n workflow.

## 🚀 Live Demo
🔗 [scan-reveal-app.lovable.app](https://scan-reveal-app.lovable.app/)

## ⚙️ How It Works
1. The Lovable frontend captures a barcode using the device camera.
2. The code is sent to an **n8n webhook**.
3. The n8n workflow:
   - Decodes the barcode
   - Searches product data (via API)
   - Returns clean product info as JSON or formatted output.

## 🧠 Tech Stack
- [n8n](https://n8n.io/) – workflow automation
- [Lovable.app](https://lovable.app/) – frontend builder
- JavaScript, HTML, CSS
- Optional APIs: BarcodeAPI, ZXing, etc.

## 🧑‍💻 Author
Built by **Abdelbari Ouamne** as a learning project.
