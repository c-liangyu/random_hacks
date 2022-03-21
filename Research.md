## 🧐 Research
### 📑 Literature
How to Read a Paper
https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf

### 📝LaTex
VS Code Latex setting (with Latex-Workshop plugin):
Add the following code to global `settings.json`.
Replace `latex-workshop.latexindent.path` to your install path.
```
    "latex-workshop.latex.tools": [
        {
            "name": "xelatex",
            "command": "xelatex",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "-pdf",
                "%DOC%"
            ]
        },
        {
            "name": "latexmk",
            "command": "latexmk",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "-pdf",
                "%DOC%"
            ]
        },
        {
            "name": "pdflatex",
            "command": "pdflatex",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%"
            ]
        },
        {
            "name": "bibtex",
            "command": "bibtex",
            "args": [
                "%DOCFILE%"
            ]
        },
        {
            "name": "makeglossaries",
            "command": "makeglossaries",
            "args": [
              "%DOCFILE%"
            ]
          }
    ],
    "latex-workshop.latex.recipes": [
        {
            "name": "pdflatex -> bibtex -> pdflatex*2",
            "tools": [
                "pdflatex",
                "bibtex",
                "pdflatex",
                "pdflatex"
            ]
        }
    ],
    "latex-workshop.latexindent.path": "/usr/local/texlive/2021/texmf-dist/scripts/latexindent/latexindent.pl",
    "latex-workshop.view.pdf.viewer": "tab",
    "[latex]": {
        "editor.wordWrap": "on",
        "editor.defaultFormatter": "James-Yu.latex-workshop"
    }
```

### 📈 Experiment

### 🗣️ Communication
How to Speak - YouTube
https://www.youtube.com/watch?v=Unzc731iCUY&ab_channel=MITOpenCourseWare

### 💾 Datasets
`Check public datasets quickly`
Roboflow Universe: Open Source Computer Vision Community
https://universe.roboflow.com/

