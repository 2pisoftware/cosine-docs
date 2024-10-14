# Contributing to these docs

We welcome anyone to contribute to the Cosine documentation. Below is a guide on how to best do so.

## Local Installation

You will need:

- [Python3](https://www.python.org/) and Pip
- Git

Then:

1. Clone this repo `git clone https://github.com/2pisoftware/cosine-docs.git`
2. Install the python dependencies `python3 -m pip install -r requirements.txt`
3. Preview the site locally `mkdocs serve`

You should now be able to make changes to the documentation and see them rendered at `https://127.0.0.1:8000`

## Writing documentation

### Guidelines

- Write content for the public. The scope of this site is specifically for information regarding the two Cosine repos [cmfive-core](https://github.com/2pisoftware/cmfive-core) and [cmfive-boilerplate](https://github.com/2pisoftware/cmfive-boilerplate). Do not include information for content outside these, such as other 2piSoftware repositories.
- Write assuming knowledge of the language and problem domain. Do not include information such as *common* PHP syntax, for example control structures like for loops or if statements.
- Cosine is Cosine. Despite the repositories being named Cmfive, please use the name Cosine when writing here unless writing specifically about one of the two repos.
- Make content searchable. Make use of specific headings and language such that users can find content using the search bar. I.e. mention the components or problem specifically instead of as a general idea.
- Include examples. When talking about usage, it is better to show than tell. Include code blocks using best practices, and code comments to explain as you go.


### Markdown extensions

This site currently has a number of mkdocs extensions enabled to allow for more versatile markdown syntax and rendering. Below is a list of the enabled extensions and their documentation.

- [Mkdocs Material Admonitions](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#usage)
- [Python Markdown Details](https://facelessuser.github.io/pymdown-extensions/extensions/details/)
- [Python Markdown Highlight](https://facelessuser.github.io/pymdown-extensions/extensions/highlight/#syntax-highlighting)
- [Python Markdown InlineHilite](https://facelessuser.github.io/pymdown-extensions/extensions/inlinehilite/)
- [Python Markdown Superfences](https://facelessuser.github.io/pymdown-extensions/extensions/superfences/)
- [Python Markdown Tabbed](https://facelessuser.github.io/pymdown-extensions/extensions/tabbed/)

## Merging to main

Once you're done writing, make a commit containing your changes and push to a new branch or fork.
Then, make a PR. It will be reviewed, changes requested if necessary, and merged into main.

Do not push directly onto main.