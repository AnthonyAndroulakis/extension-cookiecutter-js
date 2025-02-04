# JupyterLab extension-cookiecutter-js

![Github Actions Status](https://github.com/AnthonyAndroulakis/extension-cookiecutter-js/workflows/CI/badge.svg)

A [cookiecutter](https://github.com/cookiecutter/cookiecutter) template for creating
a JupyterLab extension in CommonJS JavaScript. (See also
[extension-cookiecutter-ts](https://github.com/jupyterlab/extension-cookiecutter-ts)
for an extension in TypeScript.)

## Use the template to create package

Install cookiecutter.

```
pip install cookiecutter
```

Use cookiecutter to generate a package, following the prompts to fill in the name and authorship of your new JupyterLab extension.

```
cookiecutter https://github.com/AnthonyAndroulakis/extension-cookiecutter-js
```

## A simple example

The ``lib/`` directory of your new extension includes a very simple example of a working extension, written in JavaScript using CommonJS modules. Use this example as a guide to build your own extension.

## Package name

We suggest that simple extension names start with `jupyterlab_` and use underscores if needed to improve readability, such as `jupyterlab_myextension`.
