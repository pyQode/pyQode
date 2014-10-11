![pyQode](https://raw.githubusercontent.com/pyQode/pyqode.core/develop/doc/source/_static/pyqode-banner.png)

[pyQode](https://github.com/pyQode) is a source code editor widget for PyQt/PySide.

This repository contains the [central issue tracker](https://github.com/pyQode/pyQode/issues) and the [wiki](https://github.com/pyQode/pyQode/wiki) for the pyQode project.

## Documentation

Checkout the [wiki](https://github.com/pyQode/pyQode/wiki) for getting started.

## Other repositories

pyqode is a [namespace package](http://legacy.python.org/dev/peps/pep-0382/) made up of many sub-projects. The main ones are:

### pyqode.core

[pyqode.core](https://github.com/pyQode/pyqode.core) holds the core API that provides a generic code editor and the framework needed to 
add dedicated support for a language. This package is required by all other packages except [pyqode.qt](https://github.com/pyQode/pyqode.qt).

### pyqode.python

[pyqode.python](https://github.com/pyQode/pyqode.python) adds support for the python programming languages. 

### pyqode.json

[pyqode.json](https://github.com/pyQode/pyqode.json) adds support for the json data format.

### pyqode.cobol

[pyqode.cobol](https://github.com/pyQode/pyqode.cobol) adds support for the COBOL programming language.

### pyqode.qt

[pyqode.qt](https://github.com/pyQode/pyqode.qt) provides an abstraction layer over the various Qt bindings. It supports PySide, PyQt4 and PyQt5.
This package is required by all other packages.

### pyqode-uic

[pyqode-uic]() is a tool that let you compile your qt designer ui script using the [pyqode.qt](https://github.com/pyQode/pyqode.qt) shim instead of PyQt4/PyQt5/PyQide.
