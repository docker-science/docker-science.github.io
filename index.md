---
layout: landing
title: Home
---

# Overview of Cookiecutter Docker Science

[![Build Status](https://travis-ci.org/docker-science/cookiecutter-docker-science.svg?branch=master)](https://travis-ci.org/docker-science/cookiecutter-docker-science)

Many researchers and engineers do their machine learning or data mining experiments.
For such data engineering tasks, researchers apply various tools and system libraries
which are constantly updated, installing and updating them cause problems in local environments.
Even when we work in hosting environments such as EC2, we are not free from this problem. Some experiments
succeeded in one instance but failed in another one, since library versions of each EC2 instances could be different.

By contrast, we can creates the identical Docker container in which needed tools with the correct versions are
already installed in one command without changing system libraries in host machines. This aspect of Docker is
important for reproducibility of experiments, and keep the projects in continuous integration systems.

Unfortunately working in a Docker containers is troublesome. Adding a new library into requirements.txt
or Dockerfile does not installed as if local machine. We need to create Docker image and container each time. We also need
to forward ports to see server responses such as Jupyter Notebook UI launch in Docker container in our local PC.
Cookiecutter Docker Science provides utilities to make working in Docker container simple.

This project is a tiny template for machine learning projects developed in Docker environments.
In machine learning tasks, projects glow uniquely to fit target tasks, but in the initial state, most directory
structure and targets in Makefile are common. cookiecutter-docker-science generate initial directories which fits
simple machine learning tasks.
