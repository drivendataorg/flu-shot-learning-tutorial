# Predicting Flu Vaccination: An Introduction to Machine Learning

This repository contains materials for the ["Predicting Flu Vaccination: An Introduction to Machine Learning"](https://www.goodtechfest.com/agenda/session/257154) tutorial session at [Good Tech Fest 2020](https://www.goodtechfest.com/home).

> Interested in getting started with machine learning? In this tutorial, we will walk through the full process of building a simple machine learning model using Python. We will explain the basic tools in the Python toolkit, do some light exploratory data analysis, and then build and evaluate a model.
>
> We will be using the data and prediction task from ["Flu Shot Learning,"](https://www.drivendata.org/competitions/66/flu-shot-learning/) a practice competition hosted by DrivenData: predicting whether respondents to the U.S. National 2009 H1N1 Flu Survey got H1N1 and seasonal flu vaccines using information they shared about their backgrounds, opinions, and health behaviors. DrivenData is a data science competition platform that hosts competitions exclusively in the data for social good space.
>
> As part of Good Tech Fest, DrivenData will have a special community leaderboard for conference participants. We encourage everyone to take a shot at this competition and see how your submission stacks up. We are also looking for speakers for a lightning talk session to share out your work on the competition.

## Setting up

### Setting up this project

To get this repository, the best way is to have `git` and use `git clone`:

```bash
git clone https://github.com/drivendataorg/flu-shot-learning-tutorial.git
```

This project is a simplified version of what is generated using [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/), a standardized structure we recommend for data science projects.

### Getting the data

In access the data, please sign up for the [Flu Shot Learning competition on drivendata.org](https://www.drivendata.org/competitions/66/flu-shot-learning/). Then, you can find the data on the [data download page](https://www.drivendata.org/competitions/66/flu-shot-learning/data/).

### Setting up the environment

This project requires Python 3.

Virtual environments are important for creating reproducible analyses. One popular tool for managing Python and virtual environments is [`conda`](https://docs.conda.io/en/latest/miniconda.html). You can set up the environment for this project with `conda` using the commands below.

```bash
conda create -n flu-shot-learning-tutorial python=3.7
conda activate flu-shot-learning-tutorial
pip install -r requirements.txt
```

## Project Organization

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    └── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                              generated with `pip freeze > requirements.txt`

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
