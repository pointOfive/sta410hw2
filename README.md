# UofT STA410/2102 Statistical Computation

Return to STA410 Programming Portfolio Parent Repository [here](https://github.com/pointOfive/STA410_HW/blob/master/README.md#uoft-sta4102102-statistical-computation).

## Submitting Programming Portfolio Assignment 2
Submit `sta410hw2.ipynb` file to [MarkUs](https://markus-ds.teach.cs.toronto.edu/) before the end of the calendar day (EoD) on the due date.

## Programming Portfolio Assignment 2

[Programming Portfolio Assignment 2](sta410hw2.ipynb) explores the quintessential algorithms
underlying the computational efficiency of the following standard use cases for function:

1. Interpolation with Lagrange piecewise polynomials
2. Covolution theorem with the fast Fourier transform
3. Orthogonal polynomial recurrence formula evaluation 
4. Time-benchmarking commonly used built-in functions

### Accessing Programming Portfolio Assignment 2

UofT students may access this the collection of programming problems with the [UofT JupyterHub](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw2&branch=main) or [UofT JupyterLab](https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw2&branch=main&urlpath=/lab/tree/sta410hw2) via

> [JupyterHub] https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw2&branch=main
>
> [JupyterLab] https://jupyter.utoronto.ca/hub/user-redirect/git-pull?repo=https://github.com/pointOfive/sta410hw2&branch=main&urlpath=/lab/tree/sta410hw2

Some notes to faciltate getting started in this environment are available on the UofT JupyterHub [support page](https://act.utoronto.ca/jupyterhub-support/).
If for some reason JupyterHub/Lab is not loading the repository, you can delete and reload repositories (after downloading and saving your work).  

> From JupyterHub/Lab, open a new terminal with `New` > `Terminal` and then use `yes y | rm -r <path to directory to delete>` to a delete the repository directory.

Alternatively, the programming problems may also be accessed without UofT authentication using 
[Google Colab](https://colab.research.google.com) via

> https://colab.research.google.com/github/pointOfive/sta410hw2/blob/main/sta410hw2.ipynb

### Versioning Requirements

If you're working in some other environment 
the versioning must support [notebook format 4.5](https://github.com/jupyterlab/jupyterlab/issues/9729) and 
- jupyter [notebook](https://jupyter.org/install#jupyter-notebook) version [>=6.2](https://jupyter-notebook.readthedocs.io/en/stable/) for "classic" notebooks served by [jupyterhub](https://jupyterhub.readthedocs.io/en/stable/quickstart.html)
- [jupyterlab](https://jupyter.org/install) version [>=3.0.13](https://github.com/jupyterlab/jupyterlab/releases/tag/v3.0.13) for "jupyterlab" notebooks

> You may check if cell ids are present or changing at each save with `! grep '"id":' <path/to/notebook>.ipynb`
