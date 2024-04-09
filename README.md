# ESQlabs Reports Template

This Quarto format will help you create project report for ESQlabs project. This
template includes all the formatting options to generate beautiful and clean
documents in `pdf`, `docx` and `html` formats.

  - [PDF Template Preview](template.pdf)
  - [DOCX Template Preview](template.docx)
  - [HTML Template Preview](template.html)


For more about Quarto and how to author documents using Quarto, see the [Quarto
documentation](https://quarto.org/docs/authoring/markdown-basics.html).

## Creating a New Article

You can use this as a template to create an article for the Association of
Computing Machinery. To do this, use the following command:

`quarto use template esqlabs/reports-template`

This will install the extension and create an example qmd file that you can use
as a starting place for your article.


## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From
the quarto project or document directory, run the following command to install
this format:

`quarto add esqlabs/reports-template`

## Rendering Documents

By default, the notebooks will be rendered in `html`, `pdf`, and `docx` formats.
You can render the document to all formats using the following command:

`quarto render [folder]/[file].qmd`

To render to specific format, you can use the `--to` option like this:

`quarto render [folder]/[file].qmd --to esqlabs-pdf`

of comment out the format in the `_quarto.yml` file

``` yaml
format: 
  # esqlabs-typst: default
  # esqlabs-docx: default
  esqlabs-html: default
```

## Formating options

\#ToDo

## Report Parameterization

\#ToDo