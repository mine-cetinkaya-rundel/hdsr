# HDSR 

This is a Quarto template will help you create manuscripts for 
the Harvard Data Science Review. It is based on the *HDSR* Overleaf template.
For more information see the *HDSR*
[Full Manuscript Guidelines](https://hdsr.mitpress.mit.edu/pub/guidelines-author/release/1).

## Creating a New Article

You can use this as a template to create an article for the *HDSR* journal. To do this, use the following command:

```bash
quarto use template quarto-journals/hdsr
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add quarto-journals/hdsr
```

## Usage

To use the format, you can use the format names `hdsr-pdf` and `hdsr-html`. For example:

```bash
quarto render article.qmd --to hdsr-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  hdsr-pdf:
    keep-tex: true    
```

<!-- You can view a preview of the rendered template at <https://quarto-journals.github.io/hdsr/>. -->

## Format Options

TBD
