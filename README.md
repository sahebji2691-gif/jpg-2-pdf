# JPG → PDF Converter Website

A lightweight, client-side web app that converts JPG or PNG images to a single PDF file — directly in your browser. Built with **HTML, CSS, and JavaScript**, it uses the **jsPDF** library for fast, offline conversion.

---

## ✨ Features
- 100% client-side — images never leave your browser
- Drag-and-drop image upload
- Reorder, rotate, and remove images easily
- Choose page size (A4, Letter, or custom)
- Portrait or landscape orientation
- Adjustable image quality (High / Medium / Low)
- Instant PDF download

---

## 🧠 How It Works
This app uses the [jsPDF](https://github.com/parallax/jsPDF) library to draw images onto a PDF canvas inside your browser. Once all images are added, the file is exported as a `.pdf` blob that you can download instantly.

---

## 🚀 Getting Started

### 1️⃣ Clone or download this repository
```bash
git clone https://github.com/yourusername/jpg-to-pdf.git
```

### 2️⃣ Open locally
Simply open `index.html` in your browser — no server or installation required.

### 3️⃣ Host online
You can host it free using **GitHub Pages**, **Netlify**, or **Vercel**.

---

## 🖥️ File Structure
```
jpg-to-pdf/
├── index.html   # Main web app file
├── README.md    # Project documentation
```

---

## 🌐 Deploy on GitHub Pages
1. Create a public repository.
2. Upload `index.html`.
3. Go to **Settings → Pages → Source: main branch → root**.
4. Your site will be live at:
   ```
   https://yourusername.github.io/jpg-to-pdf/
   ```

---

## 🧩 Custom Domain Setup
To connect your custom domain:
1. Add a `CNAME` file containing your domain name (e.g., `jpgpdf.in`).
2. Configure DNS records:
   - A records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - CNAME → `www` → `yourusername.github.io`
3. Enable **HTTPS** in GitHub Pages settings.

---

## 📄 License
This project is open-source under the **MIT License**.

Feel free to fork, improve, and customize it!

---

### 🧑‍💻 Author
**Your Name**  
[GitHub Profile](https://github.com/yourusername)

---
