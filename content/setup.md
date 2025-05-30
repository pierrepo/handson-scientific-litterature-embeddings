# Setup the hands-on environment

```{warning}
Manipulating embeddings requires a Python environment with specific libraries installed. It is 
essential to set up the environment correctly before starting the hands-on session.

This hands-on session assumes you have some familiarity with Python and Jupyter Lab.

During this session, you will have to download a couple of language models and datasets that may take some time, depending on your internet connection. 
```


## Install uv

`uv` is a new tool to manage Python environments and dependencies. It is similar to `pipenv` or `poetry`, but with a focus on simplicity and speed.

Install `uv` on your user session (on Linux / macOS):

```bash
$ wget -qO- https://astral.sh/uv/install.sh | sh
```

For alternative installation methods, see the [uv documentation](https://docs.astral.sh/uv/getting-started/installation/#installation-methods).

If `uv` is properly installed, you should be able to run the following command to check `uv`'s version:

```bash
$ uv self version
uv 0.7.8
```

```{note}
You might obtain a slightly different version number, which is fine. The important thing is that `uv` is installed and working.
```


## Prepare files and environment

Clone the GitHub repository with the hands-on material:

```bash
$ git clone https://github.com/pierrepo/handson-scientific-literature-embeddings
$ cd handson-scientific-literature-embeddings
```

Create a Python virtual environment and install dependencies with `uv`:

```bash
$ uv sync
```

## Let's go 🚀


Run Jupyter Lab (also with `uv`):

```bash
$ uv run jupyter lab
```

The first part of this hands-on session does not require any coding. Its goal is to help you become familiar with key concepts such as tokens and embeddings.

In the second part, you will run code to explore scientific literature using embeddings. You will use the Jupyter Lab interface to execute Python code and interact with data. We recommend starting with a new notebook and copying commands as they are provided. Take time to understand the code and its purpose. Don't worry if don't have time to complete everything during the session. This material will remain available for you to explore later at your own pace.
