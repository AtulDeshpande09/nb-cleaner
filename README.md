# 🧹 Notebook Cleaner

**Fix Jupyter Notebook rendering issues on GitHub instantly.**  
A lightweight, client-side tool to clean `.ipynb` files by removing problematic metadata, clearing outputs, and stripping execution counts.

[![Live Demo](https://img.shields.io/badge/%F0%9F%9A%80-Live%20Demo-0066cc?style=for-the-badge)](https://AtulDeshpande09.github.io/nb-cleaner/)
[![GitHub Stars](https://img.shields.io/github/stars/AtulDeshpande09/nb-cleaner?style=social)](https://github.com/AtulDeshpande09/nb-cleaner)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 🔍 Why Does This Exist?

Jupyter Notebooks often fail to render correctly on GitHub due to excessive metadata, widget states, or large outputs. This tool solves specific known issues:

| Issue | Symptom | How This Helps |
|-------|---------|----------------|
| **[Issue #3035](https://github.com/jupyter/notebook/issues/3035)** | "Sorry, something went wrong. Reload?" | Removes complex metadata that triggers renderer crashes. |
| **[Discussion #155944](https://github.com/orgs/community/discussions/155944)** | `state key missing from metadata.widgets` | Strips the problematic `widgets` block entirely. |

> 💡 **Goal:** Make your notebooks clean, readable, and version-control friendly without breaking functionality.

---

## ✨ Features

- **🔒 100% Client-Side:** Your files **never** leave your browser. No server uploads.
- **🗑️ Remove Widget Metadata:** Fixes broken renders caused by interactive widgets.
- **🧹 Clear Cell Outputs:** Removes large images/logs to reduce file size.
- **🔢 Strip Execution Counts:** Ensures clean diffs in Git (no noise from re-running cells).
- **⚡ Instant Processing:** No installation, no Python dependencies, works offline.

---

## 🚀 How to Use

1. Visit the **[Live Demo](https://AtulDeshpande09.github.io/notebook-cleaner/)**.
2. **Drag & drop** your `.ipynb` file into the browser.
3. Select cleaning options (widgets, outputs, counts).
4. Click **Download** to get your cleaned notebook.
5. Push the cleaned file to GitHub — it should now render perfectly!

---

## 🙏 Support This Project

Maintaining open-source tools takes time. If **Notebook Cleaner** helped you fix a rendering issue:

1. ⭐ **Star this repository** (it helps others find the tool!).
2. 🔗 **Share** it with a colleague struggling with GitHub previews.
3. 🐛 **Report issues** if you find a notebook that doesn't clean correctly.

[![Star on GitHub](https://img.shields.io/github/stars/AtulDeshpande09/nb-cleaner?style=social)](https://github.com/AtulDeshpande09/nb-cleaner)

---

## 🛠️ Local Development

Want to run this locally or contribute?

```bash
# Clone the repo
git clone https://github.com/AtulDeshpande09/nb-cleaner.git
cd notebook-cleaner

# Open index.html in any browser
open index.html
```
No build step required — it's pure HTML/JS!

## 📄 License
MIT License — feel free to use in personal or commercial projects.

<p align="center">
  <sup>Made with ❤️ by <a href="https://github.com/AtulDeshpande09">Atul Deshpande</a></sup>
</p>
