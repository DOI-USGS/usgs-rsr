# Usgs-rsr Format

## Installing

To install (assuming you have Quarto), run the following code in your favorite terminal:

```bash
quarto use template DOI-USGS/usgs-rsr
```

You will be asked `? Do you trust the authors of this template (Y/n) ›` type `Y` if you trust this repo.

Next, you will be asked `? Create a subdirectory for template? (Y/n) ›` type `Y` to create a new folder. Pick a name like `powell-rsr` if you're John Wesley Powell.

Then, you are asked

```bash
The template requires the following changes to extensions:
usgs-rsr   [Install]   1.0.0 (format)
? Would you like to continue (Y/n) ›
```
Type `Y` if you want to continue.

Then, a folder will be created (in our example, `powell-rsr`).
This contains a `powell-rsr.qmd` file for our example.

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

Here is the source code for a minimal sample document: [powell-rsr.qmd](powell-rsr.qmd).

