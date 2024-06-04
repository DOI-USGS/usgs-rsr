# Usgs-rsr Format

## Installing

To install (assuming you have Quarto), run the following code in your favorite terminal:

```bash
quarto use template DOI-USGS/usgs-rsr
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Using

This template is designed to help USGS scientists and developers with their Research Science Records/Development Scientist Record.
The document uses Quarto and Markdown format, but individual sections use LaTeX formatting.
Each major section is its own LaTeX file.
List formatting for the Four Factors is a little bit off, but lists are only included to include the OPM criteria.

After installing, here the steps to start writing:

1. (optionally) Rename the `qurto_rsr.qmd` file to be descriptive (for example, `Smith_rsr.qmd`).
2. Edit the `qmd` file to generate your coversheet. You may leave the pronous blank if you do not want to include them. This is the file you complie to generate the PDF.
3. Edit each `.tex` file for that seciton. You will also want to comment out the OPM guidance.

## Example

Here is the source code for a minimal sample document: [qurto_rsr.qmd](qurto_rsr.qmd).

