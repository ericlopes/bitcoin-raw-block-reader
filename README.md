# bitcoin-raw-block-reader

A simple block parser for bitcoin's raw blocks

----

## Quick links
- [Features](#features)
- [Requirements](#requirements)
- [Project Setup](#project-setup)
- [Usage](#usage)
  - [Optional Arguments](#optional-arguments)
- [Contribute](#to-contribute)
- [Project Structure](#project-structure)
- [License](#license)

----

## Features

----

## Requirements

* [python](https://www.python.org/download/releases/3.0/) >= 3.2
* *(optional)* [pip](https://pypi.python.org/pypi/pip/)
* *(optional)* [venv](https://docs.python.org/3/library/venv.html)

----

## Project Setup

* **Clone** the project
* Move into the **project dir**
* *(Optional)* Create a new **virtual environment**
* *(Optional)* Install project's **requirements**
* *(Optional)* View **documentation**
* *(Optional)* Run the **tests**
* *(Optional)* **Install** project's packages
* **Run** the project

**Step 1**: Clone the template:

    git clone https://github.com/nullhack/bitcoin-raw-block-reader.git

**Step 2**: Move into project's PATH:

    cd PATH

**Step 3**: *(Optional, but good practice)* Create a new virtual environment (VENVNAME):
  
    python3 -m venv VENVNAME
    source VENVNAME/bin/activate

If you want to deactivate the virtual environment:

    deactivate

If you are new to virtual environments, please see the `Virtual Environment section` of Kenneth Reitz's [Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/).

**Step 4**: *(Optional)* Install project's requirements:

    pip3 install -r requirements.txt

**Step 5**: *(Optional)* View documentation:

    firefox build/sphinx/html/index.html

**Step 6**: *(Optional)* Run the tests:

    python3 -m doctest -v ./tests/*
    
**Step 7**: *(Optional)* Install project's packages:

    python3 setup.py install

**Step 11**: Run the project:

    python3 main.py

----

## Usage: 

    main.py [-h] [-V]

### Optional arguments:

    -h, --help     show this help message and exit
    -V, --version  show program's version number and exit

----

## To contribute

Based on the [tutplus tutorial](https://code.tutsplus.com/tutorials/how-to-collaborate-on-github--net-34267)

The general workflow that GitHub supports is fairly simple.

* **Fork** this repo to your own account.
* **Clone** the repo to your machine.
* Check out a new **"topic branch"** and make changes.
* **Push** your topic branch to your fork.
* Use the diff viewer on GitHub to create a **pull request** via a discussion.
* Make any requested **changes**.
* The pull request is then **merged** and the "topic branch" is deleted from the upstream (target) repo.

The naming conventions for topic branches are: issue_ID, where the ID  is the ID # of a GitHub issue.

Some commands that would complete the workflow above:

**Step 1**: Forking

Fork the repo on GitHub.com, following the official guides:

* https://help.github.com/articles/fork-a-repo/
* https://guides.github.com/activities/forking/

**The easiest way** is to click on:

![Fork Button](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)

**Step 2**: Cloning

Clone the repo using this page URL:

    git clone git@github.com:YOUR_LOGIN/bitcoin-raw-block-reader.git

**Step 3**: Adding the Upstream Remote

Change into the directory and then you can add the upstream remote:

    cd python-project-builder
    git remote add upstream git@github.com:nullhack/python-project-builder.git

This will now allow you to pull in changes from the source locally and merge them, like so:

    git fetch upstream
    git merge upstream/master

**Step 4**: Checking Out a Topic Branch

Checkout a topic branch:

    git checkout -b issue_123

**Step 5**: Committing

Make your changes, and create a commit that tracks just those changes.

    git commit -am "adding some specific change."

**Step 6**: Pushing

Push this topic branch to your own fork of the project.

    git push origin issue_123

**Step 7**: Creating a Pull Request

Now you may create a pull request. First, go to your fork of the repo. You might see a "your recently pushed branches", then , you can choose "Compare and Pull Request". Otherwise, you can select your branch from the dropdown, and subsequently click "Pull Request" or "Compare" at the top right of the repo section.

----

## Project Structure

    bitcoin-raw-block-reader
    ├── docs
    │   ├── make.bat
    │   ├── Makefile
    │   └── source
    │       ├── conf.py
    │       └── index.rst
    ├── LICENSE
    ├── main.py
    ├── MANIFEST.in
    ├── block_reader
    │   ├── __init__.py
    │   └── metadata.py
    ├── README.md
    ├── requirements-dev.txt
    ├── requirements.txt
    ├── setup.py
    └── tests
        └── test_metadata.txt

----

## License

GPLv3 License

bitcoin-raw-block-reader Copyright (c) 2016 Eric Lopes


    This program comes with ABSOLUTELY NO WARRANTY;
    This is free software, and you are welcome to redistribute it
    under certain conditions.

For more info, please read the complete [license](LICENSE) file.

----

