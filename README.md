# assignment-template

> A professional LaTeX template for academic reports and assignments with predefined sections for introduction, data description, preprocessing, and appendix.

## ✨ TL;DR
```bash
pdflatex main.tex && bibtex main && pdflatex main.tex && pdflatex main.tex
```

## 🚀 Features
- **Structured chapters:** Predefined sections for Introduction, Description, Data Preprocessing, and Appendix.
- **Bibliography support:** BibTeX integration with `references.bib`.
- **Table support:** Dedicated `table.tex` for reusable table formats.

---

## 🛠️ Installation

### Prerequisites
- LaTeX distribution (e.g., TeX Live, MiKTeX)
- BibTeX

### Steps
1. Clone the repository:
```bash
git clone https://github.com/HuberNicolas/assignment-template
cd assignment-template
```
2. Compile the document:
```bash
pdflatex main.tex && bibtex main && pdflatex main.tex && pdflatex main.tex
```

---

## 💻 Usage

Open `main.tex` in a LaTeX editor (e.g., VS Code with LaTeX Workshop, or Overleaf), customize the content in the individual `.tex` files, and compile.

---

## 📄 License

This project is licensed under the **GNU General Public License v3 (GPLv3)** – see the [LICENSE](LICENSE) file for details.

**Conditions:**
- The original copyright notice (crediting my name) must be retained in all copies or substantial portions of the software.
- Modifications and derivative works *must* also be released under the GPLv3, and the source code must be made publicly available.
