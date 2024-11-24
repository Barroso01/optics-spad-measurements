# Research Paper Template

This repository contains a LaTeX template for research papers. It includes a clean directory structure and pre-configured `.cls` and `.tex` files for producing professional two-column papers.

## Repository Structure
Template/ 
|-- Bibliography/ # Contains reference files 
|-- references.bib # BibTeX bibliography file 
|-- Sections/ # Contains individual paper sections 
|-- introduction.tex # Introduction section 
|-- methods.tex # Methods section 
|-- conclusion.tex # Conclusion section 
|-- document_layout.cls # Custom LaTeX class file for paper formatting 
|-- main.tex # Main LaTeX file 
|-- main.pdf # Output PDF of the compiled paper


## How to Compile
To compile the paper from the source code, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Template.git

2. Navigate to the repository directory:
   ```bash
    cd Template

3. Compile the LaTeX source code:
    ```bash
    pdflatex main.tex
    bibtex main
    pdflatex main.tex
    pdflatex main.tex

## Notes 
- The template includes a custom LaTeX class (document_layout.cls) for consistent formatting.

- Make sure to update Bibliography/references.bib and Sections/ files with your content.


