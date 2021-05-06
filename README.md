# KTH-dES Scripts and Software Curation Guidelines

## How to publish your code online

Create a new public repository under your own Github user account or KTH-dESA.

Create a local repository (`git init`) for the script or software.
As a minimum, the repository should include:

- an appropriate open-source license
- a readme (see below)
- the source code
- a description of the software dependencies - techniques different depending on programming language

A software repository should NOT contain:

- large data files
- binary files (e.g. .exe, .pdf)
- any files which are produced as an output from running the script

## How to make a script citable

An overview:

1. Create a new public repository under your own Github user account or KTH-dESA for the script and upload it with a permission open-source license
2. Log in to Zenodo using your Github account
3. Sync the repository on Zenodo
4. Create a Github release
5. You now have an software archive on Zenodo with a citable DOI for the release

See the Github documentation on [making you code citable](https://guides.github.com/activities/citable-code/).

## How to document your code

If you are working with Python, there are powerful approaches that enable documentation to be embedded in your code.
These "docstrings" can be automatically extracted by Sphinx and rendered as web documentation or compiled into a PDF.

A `README.txt` or `README.md` file should always be written as the most fundamental documentation.

The contents depends on whether there is separate documentation.
In all cases, the readme should explain to the reader how to install and run the software.

- If there is no further documentation (e.g. the repository only contains a script), then the readme should
provide all documenation required for a user to use the script correctly.
- If there is separate documentation, then the readme should only contain fundamental installation aspects.

The contents of the readme can also contain:

- funding acknowledgement
- how to cite the code
- links to related or similar scripts or software
- information on how to contribute to the code (submit issue requests, pull requests etc.)
- some notes on future developments (what is in scope, what is not)


## How to contribute to these guidelines

You can use the [editor on GitHub](https://github.com/KTH-dESA/guidelines/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/KTH-dESA/guidelines/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
