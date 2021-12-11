<!-- Badge for License -->
<div align="right">

  [![](https://img.shields.io/github/license/yusheng910/SharedNote.svg?style=flat-square)](./LICENSE)

</div>

<!-- title, logo and description -->
<div align="center">
  <img src="https://i.imgur.com/ovfdDT8.png" alt="Shared Note" height="150px">

# Shared Note

📘 _Yu-Sheng's learning notes, proudly built with [MkDocs](https://www.mkdocs.org/) and [GitHub Actions](https://github.com/features/actions)._

</div>

## Branches

There are a three branches for difference usage here:

- [`main`](https://github.com/yusheng910/SharedNote/tree/main) hold the README for project description.
- [`docs`](https://github.com/yusheng910/SharedNote/tree/docs) store the resource code of raw notes in Markdown format.
- [`gh-pages`]([.tree/gh-pages](https://github.com/yusheng910/SharedNote/tree/gh-pages)) host the website pages published by GitHub Actions (check the [workflow file](https://github.com/yusheng910/SharedNote/blob/docs/.github/workflows/site-deployment.yaml)).

## Quick Start

```bash
# clone the project and checkout to 'docs' branch
$ git clone https://github.com/yusheng910/SharedNote
$ cd SharedNote && git checkout docs

# create the virtual environment
$ python3 -m venv env

# activate the virtual environment
$ source env/bin/activate                       # Unix-like
$ .\env\Scripts\Activate.ps1                    # Windows

# install dependencies
$ pip install -r requirements.txt

# start the server
$ mkdocs serve
```

## License

Licensed under the MIT License, Copyright © 2021-present Yu-Sheng.
