# Basic Journal Format Template

This is a Quarto template that assists you in creating a manuscript for Article Format Template journals. You can learn more about ...

## Creating a New Article

You can use this as a template to create a basic scientific article. To do this, use the following command:

```bash
quarto use template dezeraecox-manuscripts/basic
```

This will install the extension and create an example qmd file (```template.qmd```) and bibiography that you can use as a starting place for your article. For more guidance on customising these files, find the Quarto documentation [here](https://quarto.org/docs/authoring/footnotes-and-citations.html).

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension dezeraecox-manuscripts/basic
```

## Usage

To use the format, you can use the format names `basic-pdf` and `basic-html`. For example:

```bash
quarto render article.qmd --to basic-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  basic-pdf:
    keep-tex: true    
```

## Options

*TODO*: Add options that can be set via document metadata.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

## Acknowledgements

This template was created using the guidance provided by the excellent [Quarto documentation](https://quarto.org/docs/journals/formats.html), and relies heavily on the example provided in the [Biophysical Journal](https://github.com/quarto-journals/biophysical-journal) template.