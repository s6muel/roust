# roust

[![PyPI](https://img.shields.io/pypi/v/roust.svg)](https://pypi.org/project/roust/)
[![Changelog](https://img.shields.io/github/v/release/s6muel/roust?include_prereleases&label=changelog)](https://github.com/s6muel/roust/releases)
[![Tests](https://github.com/s6muel/roust/actions/workflows/test.yml/badge.svg)](https://github.com/s6muel/roust/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/s6muel/roust/blob/master/LICENSE)

A simple tool to make maintaining packages on Arch ezpz.

## Installation

Install this tool using `pip`:
```bash
pip install roust
```
## Usage

For help, run:
```bash
roust --help
```
You can also use:
```bash
python -m roust --help
```
## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:
```bash
cd roust
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
