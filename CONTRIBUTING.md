# NBA EDA Contribution Guide

This is a getting-started guide for developing on this project.

## Contents

1. Dependencies
2. Getting Started

## Dependencies

### Git

Git is an open-source, distributed version control system that allows
programmers to develop concurrently and coordinate the changes that they make.

- [Try Git](https://try.github.io/levels/1/challenges/1)

### Jupyter Notebook

Jupyter Notebook is an open-source web application that allows the creation of 
rich documents that contain both source code and its documentation.

It is included with an installation of **Anaconda**, a Python data science
platform.

- [Try Jupyter Notebook](https://try.jupyter.org/)
- [Anaconda download page](https://www.anaconda.com/download/)

## Getting Started

Basic Git commands for our project:

1. (One time only) Clone the repository (repo).
    - `git clone https://github.com/wdswihart/nba-eda`
2. Make sure you are on the `develop` branch.
    - `git checkout develop`
3. Pull changes from the remote.
    - `git pull`
4. Create and switch to a new branch for your feature.
    - `git checkout -b feature/your-feature-here`
5. Stage your changes.
    - `git add *`
6. Commit the staged changes.
    - `git commit -m "message goes here" -m "more detail if necessary"`
7. Push the commit to the remote repo.
    - `git push`

To start a Jupyter Notebook server and begin editing the document, use the command
`jupyter notebook` in the project's root folder.

More resources:

- [**pandas** documentation](http://pandas.pydata.org/pandas-docs/stable/)
