# Learning Test-Driven Development

This is a containing all the source code for the ["Learning Test-Driven Development"](https://learning.oreilly.com/library/view/learning-test-driven-development/9781098106461/) book.

## Prerequisites

Install the runtime environments for [Go](https://golang.org/), [Node.js](https://nodejs.org/en/), and [Python 3](https://www.python.org/) to run the code in this repo.

Beyond these, there are other tools -- e.g. ["act"](https://github.com/nektos/act) to run the GitHub actions locally, [gocyclo](https://github.com/fzipp/gocyclo) to check cyclomatic complexity of Go, [jshint](https://jshint.com) to do static analysis of JavaScript code, and [flake8](https://flake8.pycqa.org) for static analysis of Python code.

## How to run tests

In brief, use the following commands to run the tests for each language.

### Go

```shell
cd go
go test -v ./...
```

### JavaScript

```shell
node js/test_money.js
```

### Python

```shell
python3 py/test_money.py
```
