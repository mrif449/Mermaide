# 🌊 Mermaid Live Previewer & Editor  

A modern web-based **Mermaid.js live editor and previewer** with support for:  
- Real-time diagram rendering  
- Dark mode (blue-accent theme)  
- High-quality PNG & SVG downloads (default scale ×6)  
- Fully responsive design (optimized for all screen sizes)  

This project is a **single HTML file** solution — no backend required.  

---

## 🚀 Features  

✅ **Live Preview** — Write Mermaid diagrams in the editor and see instant updates.  
✅ **Modern Dark UI** — Sleek, blue-accent design with responsive layout.  
✅ **Export Options**  
   - Download **SVG**  
   - Download **PNG** (with scalable quality, default set to `6x`)  
✅ **Error Handling** — Shows errors when diagrams fail to render.  
✅ **All-in-One HTML** — No extra files needed.  

---

## 🛠️ Technologies Used  

- **[Mermaid.js](https://mermaid-js.github.io/)** — For rendering diagrams  
- **[Canvg](https://github.com/canvg/canvg)** — For converting SVG → Canvas → PNG  
- **HTML5, CSS3, JavaScript** — Single-file implementation  

---

## 📥 Installation & Usage  

1. **Clone or Download** this repository:  

```bash
git clone https://github.com/your-username/mermaid-live-previewer.git
cd mermaid-live-previewer
````

2. **Open `index.html`** in your favorite browser.

   * No server setup required — works offline.

3. Start writing **Mermaid code** in the editor panel.

   * Example:

   ```mermaid
   flowchart TD
       A[Start] --> B{Decision?}
       B -->|Yes| C[Option 1]
       B -->|No| D[Option 2]
   ```

4. Click **Download SVG** or **Download PNG** to export your diagram.

---

## ⚙️ Configuration

* **Default Export Quality** (PNG scale factor) is set to `6x`.
* You can change it in the script:

```js
let quality = 6; // default PNG export resolution
```

---

## 📷 Screenshots

### Main Interface

*(Add a screenshot here once available)*

---

## 🧑‍💻 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

MIT License © 2025 \[Your Name]

---

## 🙌 Acknowledgements

* [Mermaid.js](https://github.com/mermaid-js/mermaid)
* [Canvg](https://github.com/canvg/canvg)
* Inspired by modern diagramming tools but built lightweight & offline-first.