![pyQode](https://raw.githubusercontent.com/pyQode/pyQode/master/media/pyqode-banner.png)

|

[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/pyQode/pyQode?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## About
[pyQode](https://github.com/pyQode) is a source code editor widget for PyQt/PySide. You can see it as an alternative to [QScintilla](http://www.riverbankcomputing.com/software/qscintilla/intro).

This repository contains the [central issue tracker](https://github.com/pyQode/pyQode/issues) and the [wiki](https://github.com/pyQode/pyQode/wiki) for the pyQode project.

## Documentation

Checkout the [wiki](https://github.com/pyQode/pyQode/wiki) for getting started.

## License

Most of the pyqode packages are licensed under the **MIT** license.

## Other repositories

pyqode is a [namespace package](http://legacy.python.org/dev/peps/pep-0382/) made up of many sub-projects. The main ones are:

### [pyqode.core](https://github.com/pyQode/pyqode.core): 

This package holds the core API that provides a generic code editor and the framework needed to add dedicated support for a language. This package is required by all other packages except [pyqode.qt](https://github.com/pyQode/pyqode.qt).

### [pyqode.python](https://github.com/pyQode/pyqode.python)

This package adds support for the python programming languages. 

### [pyqode.json](https://github.com/pyQode/pyqode.json)

This package adds support for the json data format.

### [pyqode.cobol](https://github.com/pyQode/pyqode.cobol)

This package adds support for the COBOL programming language.

### [pyqode.qt](https://github.com/pyQode/pyqode.qt)

This package provides an abstraction layer over the various Qt bindings. It supports PySide, PyQt4 and PyQt5.
This package is required by all other packages.

### [pyqode-uic](https://github.com/pyQode/pyqode-uic)

A tool that let you compile your qt designer ui script using the [pyqode.qt](https://github.com/pyQode/pyqode.qt) shim instead of PyQt4/PyQt5/PyQide.
