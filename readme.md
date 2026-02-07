# 📐 LaTeX Laplace Transform Project

This project is configured to compile LaTeX documents using **VS Code** and the **MiKTeX** distribution. It is specifically set up to handle mathematical notation for Laplace Transforms and Differential Equations.

## 🚀 How to Compile

1. Open `test.tex` in VS Code.
2. Ensure **LaTeX Workshop** extension is active.
3. Press `Ctrl + S` (Save).
* The project is configured with a **pdflatex** recipe to avoid BibTeX errors.
* Your current settings use: `pdflatex -> bibtex -> pdflatex * 2`.



## 🛠️ Configuration Details

* **Compiler:** MiKTeX (pdfTeX 4.23).
* **VS Code Settings:** Custom `settings.json` has been updated to set `pdflatex` as the default recipe to bypass `latexmk` (Perl) dependencies.
* **Math Packages:** Uses `amsmath` and `amssymb` for high-quality mathematical rendering.

## 📚 Key Laplace Formulas

The current `test.tex` includes:

* **Definition:** 
* **Linearity:** 
* **Shifting:** 

---

## ⚠️ Troubleshooting

* **BibTeX Errors:** If you see "I found no \citation commands," ignore them. They occur because no bibliography file is present, but your PDF will still generate.
* **Missing PDF:** Click the "View LaTeX PDF" icon (magnifying glass) in the top right corner of the editor.