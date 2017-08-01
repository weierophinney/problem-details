# Problem Details for PSR-7 Applications

> ## ABANDONED
>
> This repository was used as the starting point for
> [zendframework/zend-problem-details](https://github.com/zendframework/zend-problem-details),
> and has been abandoned in favor of that repository.

[![Build Status](https://secure.travis-ci.org/weierophinney/problem-details.svg?branch=master)](https://secure.travis-ci.org/weierophinney/problem-details)
[![Coverage Status](https://coveralls.io/repos/github/weierophinney/problem-details/badge.svg?branch=master)](https://coveralls.io/github/weierophinney/problem-details?branch=master)

This library provides provides a factory for generating Problem Details
responses, error handling middleware for automatically generating Problem
Details responses from errors and exceptions, and custom exception types for
[PSR-7](http://www.php-fig.org/psr/psr-7/) applications.

## Installation

Run the following to install this library:

```bash
$ composer require weierophinney/problem-details
```

## Documentation

Documentation is [in the doc tree](doc/book/), and can be compiled using [mkdocs](http://www.mkdocs.org):

```bash
$ mkdocs build
```

You may also [browse the documentation online](https://weierophinney.github.io/problem-details/index.html).
