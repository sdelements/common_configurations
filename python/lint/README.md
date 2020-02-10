# Description

Contain common files for linting for Python.

## Files

### .flake8

The `.flake8` file contains all of the common configuration rules, as originally defined in SD Elements, as well as additional rules for other flake8-extensions. Rules for those extensions have been selected, and will lint your code against those rules if you have those extensions installed.

The following extensions are:
- [flake8-bandit](https://github.com/tylerwince/flake8-bandit): Performs security scan on the code base
- [flake8-black](https://github.com/peterjc/flake8-black): Performs checks to see if black will make any changes to the library
- [flake8-broken-line](https://github.com/sobolevn/flake8-broken-line): Checks if broken lines are used with backslashes and warn against them
- [flake8-bugbear](https://github.com/PyCQA/flake8-bugbear): Performs a check for common programming issues
- [flake8-comphrehensions](https://github.com/adamchainz/flake8-comprehensions): Checks if list/dict/set initialization can be simplified
- [flake8-docstrings](https://github.com/PyCQA/flake8-docstrings): Lints the docstrings
- [flake8-eradicate](https://github.com/sobolevn/flake8-eradicate): Warns about commented out code
- [pep8-naming](https://github.com/PyCQA/pep8-naming): Lints names on variables and functions


### pyproject.toml

Contains configurations for [Black](https://github.com/psf/black)

### requirements.txt

Contains the libraries that use these configurations.
