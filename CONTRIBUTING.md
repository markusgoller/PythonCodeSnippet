# PythonCodeSnippet Contributing Guide
Hi! I'm really excited that you are interested in contributing to PythonCodeSnippet. Before submitting your contribution, please make sure to take a moment and read through the following guidelines:

- [Style Guide](#style-guide)
- [Development Setup](#development-setup)


## Style Guide
The aim of the software is to create an easily readable and clear structure. To achieve this goal, the PEP 8 standard is complied with. Please visit page [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/) for more information.


## Development Setup
You will need [python](https://www.python.org/) **version 3.7+**, [invoke](http://www.pyinvoke.org/installing.html) **version 1.4+**, [docker](https://www.docker.com/) and [docker-compose](https://docs.docker.com/compose/).

After cloning the repo, run:

``` bash
$ python task.py local.rebuild # Building the docker containers.
$ python task.py local.python "main.py -h" # To get help and to check if the Python is installed correctly.
```
