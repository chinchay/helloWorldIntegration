# Overview

This piece of software aims to show the integration of Python, GitHub, Git, Visual Studio Code, and markdown. It is a simple greetings program for testing, and displays "Hello world!" on the screen.

Demonstration of the software running and a walktrough of the code can be found here: [Software Demo Video](https://youtu.be/bv7nygjyPV4)

# Development Environment

* Python 3.9.5
* Git / GitHub
* Visual Studio Code

## Nice to have
* Pyenv
* VScode extension `GitHub Pull Requests and Issues`

Python has been used through virtual environemnts using `pyenv` for safety and flexibility.

Useful `pyenv` commands:
```python
pyenv install -v 3.9.5
```
```python
pyenv virtualenv 3.9.5 mlbyui
```
```python
pyenv local mlbyui
```

# Useful Websites

* [Python](https://www.python.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Version Control with Git](https://www.udacity.com/course/version-control-with-git--ud123)
* [pyenv](https://realpython.com/intro-to-pyenv/)

# GitHub Token
* Update the `Personal Access Token` on GitHub, and then follow the instructions [here](https://gist.github.com/jonjack/bf295d4170edeb00e96fb158f9b1ba3c#remove-an-existing-token-from-your-mac-keychain). Doing a `git pull` will ask for username and password (your new token). 
* `git config --global credential.helper cache` will ensure the local computer remembers the token.
