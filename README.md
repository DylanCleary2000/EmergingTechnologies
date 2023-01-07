# Emerging Technologies 22/23

This repository contains my project work for the Emerging Technologies module on the Bsc (Hons) in Software Development at the 
[Atlantic Technological University](https://atu.ie).

# How to interact with this repository.
You can view the JupiterLite instance created by this repository here: [JupiterLite instance](https://dylancleary2000.github.io/EmergingTechnologies/lab/index.html).

This repository was created for a custom JupyterLite instance. JupyterLite is a lightweight version of the Jupyter Notebook, an open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text. It is designed to be easy to install and use, making it a convenient tool for data scientists, researchers, and developers who want to create interactive, reproducible documents without the need for a full Jupyter installation.

JupyterLite is implemented in Python and can be installed using the pip package manager. It can be run from the command line or as a standalone web server, making it easy to use in a variety of different environments.


## How it's set up.
To be able to run a JupyterLite instance from my repository, I installed the github actions app on my repository. I then created a new workflow file in the '.github/workflows'
directory of the repository, with specified code to be able to run the JupyterLite instance. When new changes are pushed to the repository, Github actions will automatically 
run the workflow and start a JupyterLite instance. You can access the instance in the link above.

# Notebooks

## Computation
The computation notebook contains a showcase of polynomial versus exponential growth rates illustrated using pyplot, and illustrating Big-O notation.
It discusses basic concepts of computation.
It also contains a solution for a python implemented turing machine that does not accept 1's in its input, with an explanation of how the turing machine works.

## Fourier Transform
This notebook introduces the reader to the concept of the fourier transform, as well as examples of its use, techniques for implementing it in code, and its 
applications across various scientific fields. It also has an example signal and the fast fourier transforms effect on it.

## Quantum Computing
This notebook discusses quantum computing,it's background, history and development.
It shows quantum circuit design using qiskit to illustrate.
It also discusses quantum computings applications and it's potential impact.

