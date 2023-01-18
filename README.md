# Malta Covid-19 Data Analysis

## Overview

This project provides an in-depth analysis of Covid-19 cases in Malta, utilizing the Jupyter notebook environment and various data visualization libraries. The project includes detailed instructions for setting up a local development environment, as well as instructions for deploying the project using Docker.

## Requirements

- conda

## Installation

To set up the development environment, it is recommended to use conda. If conda is already installed, simply run the following command to automatically create a conda environment with the required dependencies:

```
conda env create -f environment.yml
```

To activate the environment, run:

```
conda activate py310
```

Once the environment is set up, start Jupyter by issuing the command:

```
jupyter notebook
```

The "Malta Covid Data Analysis" notebook can then be found under the "notebooks" directory.

## Docker Deployment

Alternatively, a Docker image can be built from the provided Dockerfile for easy deployment. This image will automatically create a conda environment, install the required dependencies, and start a Jupyter notebook on port 8080.

To obtain the Jupyter token, attach a shell to the running Docker container and run the following command:

```
jupyter notebook list
```

This will display a link to the running Jupyter notebook, along with its token.

## Usage

Once the development environment is set up, the Jupyter notebook can be used to analyze and visualize the Covid-19 data. The notebook includes various data cleaning and preprocessing steps, as well as interactive visualizations of the data.
