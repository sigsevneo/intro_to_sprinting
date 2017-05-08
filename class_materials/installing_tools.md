# Installing the Software You'll Need


## Time-box

10-15 Minutes


## Overview

Collaborating on sprints generally requires the use of software tools to truly be effective and efficient. For this workshop, we will use `git` and `miniconda (conda)` to practice our skills. 

### Objectives

* Download the tools
* Install the tools
* Test for successful installation
* Review the purpose of the tools

## What to do

### Install `git`

First check to see if `git` is already installed on your computer.

Open a command prompt/terminal and type `git`

If `git` **is** installed, you will see a help document explaining some of the most common `git` commands.

If `git` **is not** installed your command prompt will tell you. Follow the instructions for your operating system:

#### Windows

1. Download the [git installer](https://git-scm.com/downloads) (**NOTE:** If you are unsure if you need the 32 or 64-bit version, you can [follow these steps](https://support.microsoft.com/en-us/help/15056/windows-7-32-64-bit-faq))

3. Run the .exe file that you downloaded and follow the instructions.

#### Mac OS

1. Download the [git installer](https://git-scm.com/downloads)

2. Open the .dmg file that you downloaded. Run the installer inside and follow the instructions.

##### Alternately, install using homebrew

Many Mac users use [homebrew](http://brew.sh/) to install programs.

```shell
brew install git
```

#### Linux

If you are running Linux, there is a good chance that you already have `git` installed. If it isn't, install it by typing one of these commands into your command prompt.

**Red Hat-based** systems (Red Hat, Centos, Fedora) use:

```bash
$ sudo yum install git-all
```

**Debian-based** systems (Ubuntu, Debian) use:

```bash
$ sudo apt-get install git-all
```

### Confirm your `git` install

In a command prompt type `git config`. If `git` is installed properly, you will see text explaining some of the common configuration options for `git`.

### Install `conda`

Follow the instructions for your operating system in the [miniconda quickstart guide](http://conda.pydata.org/docs/install/quick.html).

### Confirm your `conda` install

In a command prompt type `conda list`. If `conda` is installed properly, you will see a summary of the packages installed by `conda`.


## The big picture

### What is `git`?

`git` is a distributed version control system for managing files. It allows multiple people to work on collections of files (usually source code) and then easily *merge* other's work so everyone can have the most up to date version of the project. A later lesson will provide more details on `git`.

### What is miniconda (`conda`)?

Miniconda contains the `conda` package manager and `Python`. `conda` is language agnostic, so you can also use it to support delivering this workshop with programming languages besides `Python`. Once miniconda is installed, you will be able to create virtual environments and manage separate installations of `Python` along with a large number of Python packages/libraries. Whenever you work on a new project, you should create a separate environment for that project. `conda` lets you do this easily and efficiently. A later lesson will provide details on both virtual environments and the use of the `conda` package manager.


## Resources

* [Using conda](http://conda.pydata.org/docs/using/index.html): A tutorial on how to use `conda`

* [conda cheatsheet](https://conda.io/docs/_downloads/conda-cheatsheet.pdf): A cheatsheet of the most common `conda` commands


| Previous | Up | Next |
|:---------|:---:|-----:|
| [<prev title>](./<filename>.md) | [<section title>](./<filename>.md) | [<next title>](./<filename>.md) |