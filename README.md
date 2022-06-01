# Buddy Documentation

[![Documentation Status](https://readthedocs.org/projects/offn/badge/?version=latest)](https://offn.readthedocs.io/en/latest/?badge=latest)
[![GitHub Release](https://img.shields.io/github/v/release/Oklahoma-Friction-Free-Network/offn-documentation?style=flat-square)](https://github.com/Oklahoma-Friction-Free-Network/offn-documentation/blob/main/CHANGELOG.md)
[![GitHub License](https://img.shields.io/github/license/Oklahoma-Friction-Free-Network/offn-documentation?style=flat-square)](https://opensource.org/licenses/MIT)

A repository to host OFFN's source code for our [Read The Docs] page. Documentation is built with [Sphinx]. The latest published version of the documentation is located [here]. 

[here]: https://offn.readthedocs.io/ 

## Prerequisites

The following should be installed on your OS

- [Python 3]
- [pip] package manager
- Firefox or Chrome

Installing required Python packages with pip

``` pip install -r requirements.txt ```

[Python 3]: https://biodiversityinformatics.amnh.org/open_source/maxent/
[pip]: https://openjdk.java.net/

## Compiling documentation

The make command will be run from the project root directory. Resulting files will be placed in build

Compile: `` make clean html ``

Auto Compile: `` make clean livehtml ``
 
View: `` firefox build/html/index.html & ``

## Project Structure

```
Project Root
|  Makefile (Make file)
|  make.bat (Windows make file)
|  README.md (Project README)
|  requirements.txt (Names of required Python packages)
|
|--build (Built files)
|  | html (Generated HTML)
|  | doctrees (Binary RST Cache)
|
|--source (Source Files)
   | index.rst (Website index)
   | conf.py (Website configuration)

```

## License

* Please note that this documentation is specific to our organization. Please feel free to copy and use as needed according to the associated license. Code, documentation, and content are licensed under MIT (see LICENSE.txt) at this time. License is subject to change without notice. 
* All software mentioned within this docmentation is copyright it's respective owners. 
* [Read The Docs] and it's source code are copyrighted by Read The Docs Inc. and it's constributers

[Read The Docs]: https://readthedocs.org/
[Sphinx]: https://www.sphinx-doc.org
