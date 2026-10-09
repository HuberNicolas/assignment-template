# TODO

Open tasks for the template.

## 1. Build

- [x] Compile the 2024 version with TeX Live 2026 (pdfLaTeX + BibTeX, no errors)
- [x] Build with latexmk (`.latexmkrc`, runs biber) and in GitHub Actions; attach the PDF to releases
- [ ] Check the first workflow run on GitHub after the push

## 2. Template (v2)

- [x] Move packages, title page and macros into `assignment.sty`; chapters into `sections/`
- [x] biblatex + biber (IEEE style) instead of `cite` + BibTeX; `cleveref` for references
- [x] booktabs tables, a real code listing with caption, 2.5 cm margins, 11pt
- [x] Drop unused packages (`algorithmic`, `xparse`, `ifthen`, `textcomp`) and assignment-specific macros
- [x] Remove `table.tex` (draft notes and the course's task description), unused images and the university logos
- [x] Fix the example: "Week 444", recall rounded to 0.9974
- [ ] Optional: a German example (`\usepackage[ngerman]{babel}`)

## 3. License and release

- [x] Add the GPLv3 text the README referred to
- [ ] Decide whether GPLv3 stays or the template moves to MIT like `minimalistic-cv-template`
- [x] Tag the 2024 state as `v1.0.0` and the update as `v2.0.0`
