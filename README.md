# 📝 arXiv Two-Column LaTeX Template

A **clean, reliable, and optimized two-column LaTeX template** for arXiv preprint submissions.  
Forked and enhanced from [**myst-templates/arxiv_two_column**](https://github.com/myst-templates/arxiv_two_column), this version introduces improved compatibility, simpler usage, and better formatting.

---

## ✨ Features

- 📄 **Two-column layout** optimized for arXiv PDF submissions  
- 🔧 Customizable and lightweight: uses a single `preprint.sty` file  
- 🎯 Minimal dependencies  
- 🧩 Compatible with Overleaf and offline LaTeX environments  
- 🧾 Designed for better readability and journal-like appearance  

---

## 🚀 Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/yujmo/arXiv-template.git
cd arXiv-template
```

### 2. Basic Usage

- Use document class `\documentclass{article}`
- Copy `preprint.sty` to the directory of your `.tex` file
- Add the following line after `\documentclass`:

```latex
\usepackage{preprint}
```

- Compile `main.tex` as your starting point

---

## 📦 Project Structure

| File           | Description                                      |
|----------------|--------------------------------------------------|
| `preprint.sty` | The core style file                             |
| `main.tex`     | A sample LaTeX document using the template       |
| `main.bib`     | BibTeX bibliography file                         |

---

## 📚 arXiv Submission Tips: Include the `.bbl` File

To ensure **correct bibliography rendering on arXiv**, you must **manually include** the `.bbl` file if you're using **BibTeX**.

### ✅ How to Get `main.bbl` from Overleaf

1. **Compile** your project successfully on Overleaf  
2. Click **"Logs and output files"** on the left panel  
3. **Open** the `.bbl` file  
4. **Copy all contents**, paste into a local file, save as `main.bbl`  
5. Upload `main.bbl` back to Overleaf or your GitHub repo

> ⚠️ **Important:** arXiv does **not run BibTeX**. If you forget to include `main.bbl`, your references will not compile correctly.

---

## 💡 Why Two-Column?

The two-column format:
- 🧠 Enhances readability
- 📑 Mimics journal layouts
- ✅ Looks clean and professional
- 📐 Optimized for space efficiency

---

## 📌 Notes & Credits

- 📧 **Contact:** yujmo@qq.com  
- 📅 **Version:** v1.0 (July 10, 2025)  
- 🙏 Template inspired by: [myst-templates/arxiv_two_column](https://github.com/myst-templates/arxiv_two_column)

---

## 🤝 Contributing

We welcome all contributions!

- Report bugs or submit feature requests via Issues
- Submit improvements via Pull Requests

---

## 📄 License

This project is open-source and free to use.  
⚠️ The author assumes **no responsibility** for any use of this template.

Attribution is appreciated if you reuse or modify this template in your own project.

---
