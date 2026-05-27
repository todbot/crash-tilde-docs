# crash-tilde-docs

Documentation site for [tilde.crashspace.org](https://tilde.crashspace.org/), 
a shared Unix tilde server for members run by the 
[CrashSpace](https://crashspace.org/) hackerspace community.

Built with [MkDocs](https://www.mkdocs.org/) using the [mkdocs-terminal](https://github.com/ntno/mkdocs-terminal) theme.

## Prerequisites

- Python 3.x
- `mkdocs`
- `mkdocs-terminal`

Install dependencies:

```bash
pip install mkdocs mkdocs-terminal
```

## Development

Serve locally with live reload:

```bash
mkdocs serve --livereload
```

Then open [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Build

```bash
mkdocs build
```

Output goes to `site/`.
