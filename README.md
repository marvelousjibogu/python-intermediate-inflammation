# Introduction

This is a template software project repository used by the [Intermediate Research Software Development Skills In Python](https://github.com/carpentries-incubator/python-intermediate-development).

## Purpose

This repository is intended to be used as a code template which is copied by learners at [Intermediate Research Software Development Skills In Python](https://github.com/carpentries-incubator/python-intermediate-development) course.
This can be done using the `Use this template` button towards the top right of this repo's GitHub page.

This software project is not finished, is currently failing to run and contains some code style issues. It is used as a starting point for the course - issues will be fixed and code will be added in a number of places during the course by learners in their own copies of the repository, as course topics are introduced.

## Tests

Several tests have been implemented already, some of which are currently failing.
These failing tests set out the requirements for the additional code to be implemented during the workshop.

The tests should be run using `pytest`, which will be introduced during the workshop.

# Inflam
![Continuous Integration build in GitHub Actions](https://github.com/marvelousjibogu/python-intermediate-inflammation/workflows/CI/badge.svg?branch=test-suite)
Inflam is a data management system written in Python that manages trial data used in clinical inflammation studies.

## Main features
Here are some key features of Inflam:

- Provide basic statistical analyses over clinical trial data
- Ability to work on trial data in Comma-Separated Value (CSV) format
- Generate plots of trial data
- Analytical functions and views can be easily extended based on its Model-View-Controller architecture

## Prerequisites
Inflam requires the following Python packages:

- [NumPy](https://www.numpy.org/) - makes use of NumPy's statistical functions
- [Matplotlib](https://matplotlib.org/stable/index.html) - uses Matplotlib to generate statistical plots

The following optional packages are required to run Inflam's unit tests:

- [pytest](https://docs.pytest.org/en/stable/) - Inflam's unit tests are written using pytest
- [pytest-cov](https://pypi.org/project/pytest-cov/) - Adds test coverage stats to unit testing
