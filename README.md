<!-- This is my GitHub README -->
<!-- It describes what this repostitory is for -->
# Emerging Technologies Submission 2022/2023

[![Python badge](https://img.shields.io/badge/language-python3-blue)](https://www.python.org/)
[![Jupyter notebook badge](https://img.shields.io/badge/Jupyter%20Notebook-orange)](https://github.com/G00378925/emerging-technologies/search?l=jupyter-notebook)<br>

**Declan Kelly** - **G00378925**<br>

This repository contains my assessment submission for my university module [Emerging Technologies](https://www.gmit.ie/emerging-technologies)[0].

In this module you are encouraged to explore the state of the art in programming languages, messaging protocols and the future of computing.

All material that will be assessed will be stored inside Jupyter notebooks, normally you would have to download to run these,
but I have an instance of JupyterLab running on GitHub pages that runs inside your browser without having to install anything.

JupyterLite instance: [https://g00378925.github.io/emerging-technologies](https://g00378925.github.io/emerging-technologies)

The topics to be covered in this assessment[1], are the following:
1. GitHub Pages and Actions
2. JupyterLite
3. Computation
4. Fourier Transform
5. Quantum Computing

## JupyterLite instance
JupyterLite is lightweight, web-based version of [JupyterLab](https://jupyter.org/).
In this project, an instance of JupyterLite[2] is hosted on GitHub pages.

To make is easier for people who may not have JupyterLab installed,
I am using [GitHub Actions](https://docs.github.com/en/actions)
to automatically build and deploy a version of JupyterLite to [GitHub Pages](https://pages.github.com/).

Whenever a commit is pushed to the repostitory, the GitHub action described in
[.github/workflows/deploy.yml](.github/workflows/deploy.yml) is executed,
building and deploying a version of JupyterLite, bundling my notebooks alongside it.

For more information on this will be explained in the `01-github-pages.ipynb` and `02-jupyterlite.ipynb` notebook.

## Troubleshooting
1. All notebooks except `05-quantum-computing.ipynb` (requires Qiskit, which isn't supported yet) should work out of the box in JupyterLite.
2. Do not rely on GitHub to display the notebooks correctly (as seen in the `01-github-pages.ipynb`), you should use JupyterLite instead.
3. If JupyterLite is showing an older version of the notebooks, you should open the JupyterLite instance in a private tab in your browser.
4. Any additional problems should be solved by restarting the kernel and running all cells (`Kernel`>`Restart Kernel and Run All Cells...`) in Jupyter.

## References
[0] https://www.gmit.ie/emerging-technologies<br>
[1] https://github.com/ianmcloughlin/2223-S1-emerging-technologies/blob/main/introduction/2223-emerging-technologies-intro.pdf<br>
[2] https://github.com/jupyterlite/demo
