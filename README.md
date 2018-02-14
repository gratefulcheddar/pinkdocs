# pinkdocs
Developer Documentation for Pinkcoin

This is currently a work in progress. The website can be previewed at (https://gratefulcheddar.github.io/pinkdocs).

### Installation

Pinkdocs uses [MkDocs](https://mkdocs.org), which uses Python, HTML, and CSS to build documentation from simple Markdown files. Installation instructions for MkDocs can be found [here](http://www.mkdocs.org/#installation).

After downloading this repo, use the `mkdocs serve` terminal command in the Pinkdocs directory and open a browser to (localhost:8000) to run your own local documentation. This will auto-reload when any changes are made to the source code.


### Directory Structure
```
.
├── _mkdocs.yml (config)
├── _LICENSE 
├── _README.md
├── _src/ (markdown, images)
├── _docs/ (mkdocs build target)
└── _mkdocs-material/ (theme) 
```

### Contributing

To report an issue, use Github's issue [here](https://github.com/gratefulcheddar/pinkdocs/issues).


To add or edit the source code, [fork](https://github.com/gratefulcheddar/pinkdocs#fork-destination-box) your own copy of this repository and submit a new pull request with your changes.

> WARNING: Do not run the `mkdocs build` command. This will build the static pages of this website and place them in the `docs/` directory. Repo maintainers should update the static pages after updates/pull requests are merged.

##### To create a new page:
- Create a markdown file in the `src/` directory.
- Add the file to the pages section of `mkdocs.yml`




