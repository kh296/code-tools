# code-tools

Conda environment providing tools for formatting, profiling,  and testing
Python code, and for counting lines of code.

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

- [pytest](https://docs.pytest.org/)
```
pytest [file_or_directory]
```

- [pytest-cov](https://pytest-cov.readthedocs.io/)
(Used with `pytest`.)
```
pytest --cov=<path_to_package> <path_to_tests>
```

- [Python profilers](https://docs.python.org/3/library/profile.html)
```
python -m cProfile [-o output_file] <python_script>
```

- [SnakeViz](https://jiffyclub.github.io/snakeviz/)
```
snakeviz <cProfile_output_file>
```
