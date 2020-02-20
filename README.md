# .python

A template repository for Python.

## Setup

```
$ git clone https://github.com/micnncim/.python repo
$ cd repo
$ rm -rf .git
$ git init
$ git remote add origin https://github.com/owner/repo
$ rm -f README.md
$ mv README.tmpl.md README.md
$ fd -E .git -X sd '<<OWNER>>' 'owner'
$ fd -E .git -X sd '<<PROJECT>>' 'repo'
$ fd -E .git -X sd '<<YEAR>>' '2020'
```

## Development

This project contains the following development tools:

- [Pipenv](https://pipenv.kennethreitz.org/en/latest)
- [Mypy](https://github.com/python/mypy)
- [Black](https://github.com/psf/black)

