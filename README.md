# Deep Thinking — A LaTeX Learning Project
This repository contains a personal LaTeX project titled **Deep Thinking**, created solely for the purpose of learning how to write structured and professional documents using LaTeX. The content is secondary; the primary goal is to understand and experiment with LaTeX’s capabilities for large-scale writing projects.

## Project Description
**Deep Thinking** is a mock book inspired by https://arxiv.org/abs/2201.00650 style that explores the intersection between artificial intelligence, neural networks, and human cognition. While the topic itself is intriguing, the actual intention of this project is to learn how to effectively structure a LaTeX document, manage chapters, include references, and format content in a clean, academic layout.

The project demonstrates:

- Multi-chapter document structure
- Automatic table of contents
- Cross-referencing and citations
- Use of packages such as `amsmath`, `graphicx`, `hyperref`, etc.
- Bibliography management (BibTeX-ready)
- Customizable formatting

## Project Structure

```text
.
├── compile.sh # for compiling script
├── main.aux
├── main.lof
├── main.log
├── main.lot
├── main.maf
├── main.mtc
├── main.mtc0
├── main.out
├── main.pdf # the output
├── main.tex # main source code
├── main.toc
├── README.md
└── texput.log

1 directory, 14 files
```

## Compilation Instructions
Ensure you have a LaTeX distribution installed, such as **TeX Live**, **MiKTeX**, or **Overleaf**.

To compile manually via command line:

```bash
pdflatex main.tex
bibtex main           # Only if bibliography is used
pdflatex main.tex
pdflatex main.tex

# or run the bash file (usinh xelatex)
./compile.sh
```
The output will be a `main.pdf` file.

## Learning Goals

- Practice with LaTeX fundamentals
- Build and manage a long-form document
- Experiment with:
  - Mathematical environments
  - Floating figures and tables
  - Cross-references
  - Citations and bibliography
  - PDF hyperlinking and formatting

## License
This project is for personal learning purposes only and is not licensed for redistribution. Feel free to fork and use as a reference or template for your own LaTeX experiments.

## Author
Created by [Fauzy](http://fauzy.lovestoblog.com) as part of a self-guided LaTeX learning journey.

## Reference
- [Deep Learning Interviews: Hundreds of fully solved job interview questions from a wide range of key topics in AI](https://arxiv.org/abs/2201.00650)
- [HTN Plan Repair Algorithms Compared: Strengths and Weaknesses of Different Methods](https://arxiv.org/pdf/2504.16209)
- [Neural Thermodynamic Laws for Large Language Model Training](https://arxiv.org/pdf/2505.10559)
