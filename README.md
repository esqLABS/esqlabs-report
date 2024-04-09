# ESQlabs Reports Template

This Quarto format will help you create documents for ESQlabs project. For more about Quarto and how to use format extensions, see <https://quarto.org/docs/journals/>.

## Creating a New Article

You can use this as a template to create an article for the Association of Computing Machinery. To do this, use the following command:

```quarto use template esqlabs/reports-template```

This will install the extension and create an example qmd file that you can use as a starting place for your article.


## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```quarto add esqlabs/reports-template```

## Usage 

To use the format, you can use the format names `esqlabs-pdf` and `esqlabs-html`. For example:

```quarto render article.qmd --to esqlabs-pdf```

or in your document yaml

```yaml
format:
  pdf: default
  esqlabs-pdf
```

