# code-tools

Conda environment providing tools for formatting Python code,
and for counting lines of code.

- [autopep8](https://github.com/hhatto/autopep8)
```
# -i : make changes to file in place.
# --max-line-length : maximum line length.
# -a : enable agressive (non-whitespace) changes; repeat to increase agression.
autopep8 -i --max-line-length 80 -a -a <file>
```
- [black](https://black.readthedocs.io/)
```
# -l : maximum line length.
black -l 80 <file_or_directory>
```
- [pylint](https://pylint.pycqa.org/)
```
pylint <module_or_package>
```

- [pygount](https://pygount.readthedocs.io/)
```
pygount --format=summary <file_or_directory>
```
