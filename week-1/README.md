Week 1
========

In our first week, we'll be focusing on getting a development environment set
up. The instructions are currently aimed at macOS, however more operating
systems will be added soon.

> The beginning is the most important part of the work — Plato

Let's get to it!


Getting Started
-----------------

We'll need to install quite a few tools to set up a development environment.
Homebrew is useful a package manager and repository for macOS; we'll use this
to install all the packages we need.

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```


Next, we'll need to install the programming language package itself.

```
brew install python3
```

Editing code requires an editor which only outputs exactly what you intended to
type, we'll use Visual Studio Code as a good first editor.

```
brew cask install visual-studio-code
code --install-extension donjayamanne.python
```

We don't always write all the code that we use, collaboration is essential when
writing code. Libraries are shared collections of code, usually written by
somebody else. To avoid cross-interaction of different library versions, we use
*virtual environments* to isolate them.

```
pip3 install virtualenv
pip3 install virtualenvwrapper
```
