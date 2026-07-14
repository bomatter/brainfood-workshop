# Brainfood EEG Deep Learning Workshop

A hands-on introduction to deep learning for EEG data.

## Setup

1. You should be able to run Jupyter notebooks with the dependencies listed in this repo (`pyproject.toml`).

   One way to do this is to use [uv](https://docs.astral.sh/uv/) to install the dependencies. Install uv following the [instructions on their website](https://docs.astral.sh/uv/getting-started/installation/), then run `uv sync` in the repository root.

   VS Code can be used to open and run notebooks and you can select the environment created by uv for the notebook kernel. Alternatively, if you don't have an IDE like VS Code with notebook support, you can use `uv run jupyter lab` to open notebooks in a browser.

2. Download and unzip the data from NEMAR: https://ww2.nemar.org/dataset/nm000139

3. To test your setup, run the first few cells in the `demo.ipynb` notebook.

