
## Description:

This LaTeX template is a customized and optimized two-column format for arXiv preprint submissions, forked and enhanced from  [**myst-templates/arxiv_two_column**](https://github.com/myst-templates/arxiv_two_column).

It is ideal for researchers seeking a reliable and well-tested two-column arXiv template with tailored improvements. The template maintains the clean and professional layout of the original while introducing enhancements for better compatibility, streamlined dependencies, and personalized formatting adjustments.

---
Version 1.0 — July 10, 2025

## Project files:
1. **preprint.sty** - the style file.
2. **main.tex** - a sample template that uses the **preprint style**.
3. **main.bib** - the bibliography source file for main.tex.

### Why two-column? 
Because the two-column styling is a comfortable format that is very esthetic and convenient for reading.

## Usage:
1. Use Document class **article**. 
2. Copy **preprint.sty** to the folder containing your tex file.
3. add `\usepackage{preprint}` after `\documentclass{article}`.

See **main.tex** 


## 📚 arXiv Submission: Include the `.bbl` File

To ensure **correct bibliography compilation** and avoid errors when submitting to platforms such as **arXiv**, it's **essential to include the `.bbl` file** from your Overleaf project.

### ✅ Step-by-Step Instructions

1. **Compile** your Overleaf project successfully.
2. On the left sidebar, click **“Logs and output files”**.
3. Scroll down and **locate the `.bbl` file**.
4. Click to **open the `.bbl` file**, then:
   - **Copy all contents**
   - Paste into a **local text file**
   - Save it with the extension: `.bbl`
   - **Rename the file to:** `main.bbl`
5. **Upload `main.bbl`** back into your Overleaf project.

### 📦 Why This Matters

- ✅ The `.bbl` file will be **included when downloading the ZIP archive** from Overleaf.
- ✅ It ensures **offline LaTeX compilers** (including arXiv's) can render your bibliography correctly.
- ✅ Prevents **compilation errors** due to missing bibliography.
- ✅ Guarantees **consistent and accurate reference formatting** across platforms.

> ⚠️ **Note:** arXiv compiles using a non-interactive LaTeX pipeline that does **not run BibTeX**. Including `main.bbl` is **mandatory** if you use BibTeX-based references.


## 📌 General Notes

> 💡 If you are using or building upon this project, please take note of the following:

### 📬 1. Contact  
For help, feedback, or bug reports, feel free to contact the author:  
📧 **yujmo@qq.com**

---

### 📄 2. License & Responsibility  
You are free to **use**, **redistribute**, and **modify** this project.  
⚠️ **Disclaimer:** The author **takes no responsibility** for any consequences of using this project.

---

### 🔗 3. Attribution Encouraged  
If you create another project based on this work, it would be **appreciated** if you could mention or link back to this repository.

---

### 🤝 4. Contributions Welcome  
**Pull requests** and contributions are very welcome!  
Whether it's a typo fix or a new feature—you're invited to help improve the project.
