# LaTeX

This folder contains templates and instructions for generating reports using LaTeX with Quarto.

## Prerequisites

1. Install Quarto: Follow the instructions on the [Quarto website](https://quarto.org/docs/get-started/).
2. Install TinyTeX: Run `quarto install tinytex`. If it asks you whether you want to make updates, say yes.

## Instructions

1. Navigate to the `latex` folder:

   ```sh
   cd latex
   ```

2. Make your edits to the `report.qmd` document.
3. To preview the document as HTML, run:

   ```sh
   quarto preview report.qmd --to html
   ```

4. To render the document as a PDF, run:

   ```sh
   quarto render report.qmd --to pdf
   ```

For more information on using Quarto with LaTeX, refer to the [Quarto documentation](https://quarto.org/docs/output-formats/pdf/).
