# Python Projects
This page provides notes and potential resources for the management of python
projects, especially wrt packaging them and publishing to PyPi (or to wheel
file).

https://packaging.python.org/en/latest/key_projects/#pypa-projects


## Project
foo

## Package
While one can package a Python project simply using built-ins,
it is safer (and less work) to utilize packaging/project tooling
such as:

- [Hatch](https://hatch.pypa.io/latest/)
- [Flit](https://flit.pypa.io/en/latest/)

For further reading on packaging, there are some great resources:
- [Overview of packaging](https://packaging.python.org/en/latest/overview/)
  - [Packaging flow](https://packaging.python.org/en/latest/flow/)
  - [Guides](https://packaging.python.org/en/latest/guides/)



## Publish

- `twine`: the standard
- [Bandersnatch](https://github.com/pypa/bandersnatch): Pypi-mirroring client to test things out
