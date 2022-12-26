<!-- This is my GitHub README -->
<!-- It describes what this repostitory is for -->
# Emerging Technologies Submission 2022/2023
**Declan Kelly** - **G00378925**<br>

This repository contains my assessment submission for my university module [Emerging Technologies](https://www.gmit.ie/emerging-technologies)[0].

In this module you are encouraged to explore the state of the art in programming languages, messaging protocols and the future of computing.

All material that will be assessed will be stored inside Jupyter notebooks, normally you would have to download to run these,
but I have an instance of JupyterLab running on GitHub pages that run inside your browser without having to install anything.

JupyterLite instance: [https://g00378925.github.io/emerging-technologies](https://g00378925.github.io/emerging-technologies)

The topics to be covered in this assessment[1], are the following:

1. GitHub Pages and Actions
    1. What is a server?
    2. 
3. JupyterLite
4. Computation
    1. Growth rates/Big O notation
    2. Turing machine
5. Fourier Transform
6. Quantum Computing
    1. 

## JupyterLite instance

JupyterLite is lightweight, web-based version of [JupyterLab](https://jupyter.org/).
In this project, an instance of JupyterLite [2] is hosted on GitHub pages.

To make is easier for people who may not have JupyterLab installed,
I am using [GitHub Actions](https://docs.github.com/en/actions)
to automatically build and deploy a version of JupyterLite to [GitHub Pages](https://pages.github.com/).

Whenever a commit is pushed to the repostitory, the GitHub action described in
[.github/workflows/deploy.yml](.github/workflows/deploy.yml) is executed,
building and deploying a version of JupyterLite, bundling my notebooks alongside it.

For more information on this:

1. `01-github-pages.ipynb`: This notebook explains how you can use
GitHub Pages and GitHub Actions to setup your own automically deploying JupyterLite.
2. `02-jupyterlite.ipynb`: This notebook explains how JupyterLab
in the browser is made possible using [Pyodide](https://pyodide.org/en/stable/).

## References

[0] https://www.gmit.ie/emerging-technologies<br>
[1] https://github.com/ianmcloughlin/2223-S1-emerging-technologies/blob/main/introduction/2223-emerging-technologies-intro.pdf<br>
[2] https://github.com/jupyterlite/demo