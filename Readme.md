# tfCutter

A cookiecutter template for generating a simple tensorflow class.

Have you noticed that generating a new tensorflow class for a new classification task is very repetitive. Would it not be nice if it were possible to generate something that already takes care of the boilerplate, and lets you deal with the generation of the code. Sure, there is Keras. However, I feel that Keras is sometiles a little too high-level for my tasks, and does not fit nicely into my workflow. Hence, this scaffolding framework that allows us to generate something within Tensorflow, all the while keeping with the nature of the general project structure.

This is intended to be used as part of the [myCutter](https://github.com/sankhaMukherjee/tfCutter) template and is not supposed to be a standalone installation.

## Getting Started

Install cookiecutter

```bash
pip3 install -U cookiecutter
```

Generate a python package:

```bash
cookiecutter https://github.com/sankhaMukherjee/myCutter
```

Now, initialize the project, switch to a virtual environment, and install this in the lib folder

```bash
cd [<project Folder>]
make firseRun
source env/bin/activate
cd src/lib
cookiecutter https://github.com/sankhaMukherjee/tfCutter
```

## Prerequisites

You will need to have a valid Python installation on your system. This has been tested with Python 3.6. It does not assume a particulay version of python, however, it makes no assertions of proper working, either on this version of Python, or on another. 

## Built For

 - Python 3.6

## Contributing

Please send in a pull request.

## Authors

Sankha S. Mukherjee - Initial work (2018)

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.
 