# winzy-time-in-words

[![PyPI](https://img.shields.io/pypi/v/winzy-time-in-words.svg)](https://pypi.org/project/winzy-time-in-words/)
[![Changelog](https://img.shields.io/github/v/release/sukhbinder/winzy-time-in-words?include_prereleases&label=changelog)](https://github.com/sukhbinder/winzy-time-in-words/releases)
[![Tests](https://github.com/sukhbinder/winzy-time-in-words/workflows/Test/badge.svg)](https://github.com/sukhbinder/winzy-time-in-words/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/sukhbinder/winzy-time-in-words/blob/main/LICENSE)

Simple program to say time in words

## Installation

First [install winzy](https://github.com/sukhbinder/winzy) by typing

```bash
pip install winzy
```

Then install this plugin in the same environment as your winzy application.
```bash
winzy install winzy-time-in-words
```
## Usage

To get help type ``winzy  time --help``

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:
```bash
cd winzy-time-in-words
python -m venv venv
source venv/bin/activate
```
Now install the dependencies and test dependencies:
```bash
pip install -e '.[test]'
```
To run the tests:
```bash
python -m pytest
```
