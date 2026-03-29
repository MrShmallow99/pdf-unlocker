# 🔓 Secure PDF Unlocker

A fully client-side web application to remove password protection from PDF files. 

## 🌟 Why this tool?
Most online PDF unlockers require you to upload your sensitive documents (like bank statements or tax forms) to a remote server. This poses a massive privacy and security risk. 

**Secure PDF Unlocker** processes everything 100% locally in your web browser. Your files and passwords never leave your device.

## ✨ Features
* **Zero Uploads:** Complete client-side processing. No servers, no tracking.
* **Preserves Quality:** Uses a native WebAssembly port of QPDF (`qpdf-wasm`). Unlike naive canvas-based approaches, it preserves all selectable text, original formatting, hyperlinks, and document structure.
* **Universal Decryption:** Supports all standard PDF encryption algorithms.
* **Modern UI:** Clean, responsive, and user-friendly interface.

## 🛠️ Technology Stack
* **Frontend:** Vanilla HTML, CSS, and JavaScript (No heavy frameworks).
* **PDF Engine:** [@neslinesli93/qpdf-wasm](https://github.com/neslinesli93/qpdf-wasm) (A WebAssembly port of the robust C++ QPDF library).
* **Hosting:** Vercel (Static deployment).

## 🚀 How to Use
1. Drag and drop a password-protected PDF into the drop zone.
2. Enter the document's password.
3. Click "Unlock PDF".
4. Download your clean, unprotected PDF.

## 📜 License
This project is open-source and free to use.
