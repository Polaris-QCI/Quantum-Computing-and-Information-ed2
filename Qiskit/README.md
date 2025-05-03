# Quantum Computing and Information: A Scaffolding Approach (2nd Edition)

This folder contains [Qiskit](https://www.ibm.com/quantum/qiskit) code samples for the textbook *Quantum Computing and Information: A Scaffolding Approach (2nd Edition)* by Peter Lee, Huiwen Ji, and Ran Cheng.

## Copyright

© John Hurst and Peter Lee, Published by Polaris QCI Publishing.

## Engaging with the Repository

We encourage readers to actively participate in this repository and contribute to its growth. Here's how you can engage:

### Explore and Use the Code

* Dive into the provided Jupyter notebooks (`.ipynb` files) and experiment with the code examples.
* Run the simulations and observe the results.
* Modify the code to explore different scenarios and deepen your understanding.

### Provide Feedback and Suggestions

* **Open Issues:** If you find any errors, have suggestions for improvements, or encounter any issues, please open an issue on GitHub.
* **Discuss Concepts:** Use the issue tracker to discuss specific concepts, ask questions, or share your insights.
* **Request New Content:** Suggest topics or examples you'd like to see added to the repository.

### Contribute Code and Content

* **Fork and Pull Requests:** If you have improvements in the code or documentation, new examples, or additional learning materials, fork the repository, make your changes, and submit a pull request.
* **Contribute Notebooks:** Create new Jupyter notebooks that illustrate specific concepts or provide additional examples.

#### Example Issue/Pull Request Ideas

* "Found a typo in the teleportation demo notebook."
* "Suggest adding an example of E91's algorithm implementation."

### Engage in Discussions

* **Follow the Repository:** Stay updated on new releases and discussions by following the repository.
* **Participate in Discussions:** Join existing discussions and share your thoughts.

**How to Contribute:**

1.  **Fork the repository:** Click the "Fork" button in the top right corner of the repository page.
2.  **Clone your fork:** Clone the forked repository to your local machine.
3.  **Create a branch:** Create a new branch for your changes.
4.  **Make your changes:** Modify the code, add new content, or improve documentation.
5.  **Commit your changes:** Commit your changes with descriptive commit messages.
6.  **Push your changes:** Push your changes to your forked repository.
7.  **Create a pull request:** Click the "New pull request" button on your forked repository page.

We believe that collaborative learning is essential for understanding quantum computing. We look forward to your contributions and engagement!

## Local Setup

The code is in the form of Python Jupyter notebooks.

You can run the code locally, or in the cloud using one of several Jupyter hosting services.

To run the notebooks locally, we recommend using [uv](https://docs.astral.sh/uv/) to manage your Python environment.
Follow the instructions for "macOS and Linux" if you are using macOS, Linux, or WSL2.
Follow the instructions for "Windows" if you are using Windows.
You may need to update your `PATH` environment variable to include the location of the `uv` executable.

Once you have `uv` installed, sync the project and create your virtual environment using the following commands:

```
cd Qiskit
uv sync
```

You can run the Jupyter notebooks locally in several ways:

* Using [Visual Studio Code](https://code.visualstudio.com/).
* Using [PyCharm](https://www.jetbrains.com/pycharm/).
* Using `jupyter-notebook` on the command line.

To use Visual Studio Code or PyCharm, open the project in the IDE and select the virtual environment you created with `uv`.

To use `jupyter-notebook`, initialize the virtual environment first:

On maxOS, Linux, or WSL2:

``` bash
source .venv/bin/activate
```

On Windows (PowerShell):

``` powershell
.venv\Scripts\activate.ps1
```

On Windows (Command Prompt):

``` cmd
.venv\Scripts\activate.bat
```

Then, run the Jupyter notebook server:

``` bash
jupyter-notebook
```

## Cloud Services

You can also run the Jupyter notebooks Cloud-hosted notebook services such as [Binder](https://mybinder.org/) or [Google Colab](https://colab.research.google.com/).

Links for each sample for Binder and Colab are below:

### bb84-quantum-key-distribution-demo

[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Polaris-QCI/Quantum-Computing-and-Information-ed2/main?labpath=Qiskit%2F05-Single-Qubit-Quantum-Gates%2Fbb84-quantum-key-distribution-demo.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polaris-QCI/Quantum-Computing-and-Information-ed2/blob/main/Qiskit/05-Single-Qubit-Quantum-Gates/bb84-quantum-key-distribution-demo.ipynb)

### quantum-coin-game-demo

[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Polaris-QCI/Quantum-Computing-and-Information-ed2/main?labpath=Qiskit%2F05-Single-Qubit-Quantum-Gates%2Fquantum-coin-game-demo.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polaris-QCI/Quantum-Computing-and-Information-ed2/blob/main/Qiskit/05-Single-Qubit-Quantum-Gates/quantum-coin-game-demo.ipynb)

### teleportation-demo

[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Polaris-QCI/Quantum-Computing-and-Information-ed2/main?labpath=Qiskit%2F10-Key-Applications-of-Entanglement%2Fteleportation-demo.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polaris-QCI/Quantum-Computing-and-Information-ed2/blob/main/Qiskit/10-Key-Applications-of-Entanglement/teleportation-demo.ipynb)

### e91-quantum-key-distribution-demo

[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Polaris-QCI/Quantum-Computing-and-Information-ed2/main?labpath=Qiskit%2F10-Key-Applications-of-Entanglement%2Fe91-quantum-key-distribution-demo.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polaris-QCI/Quantum-Computing-and-Information-ed2/blob/main/Qiskit/10-Key-Applications-of-Entanglement/e91-quantum-key-distribution-demo.ipynb)

### 3-qubit-bitflip-demo

[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Polaris-QCI/Quantum-Computing-and-Information-ed2/main?labpath=Qiskit%2F13-Quantum-Error-Correction%2F3-qubit-bitflip-demo.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polaris-QCI/Quantum-Computing-and-Information-ed2/blob/main/Qiskit/13-Quantum-Error-Correction/3-qubit-bitflip-demo.ipynb)

### 3-qubit-phaseflip-demo

[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Polaris-QCI/Quantum-Computing-and-Information-ed2/main?labpath=Qiskit%2F13-Quantum-Error-Correction%2F3-qubit-phaseflip-demo.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polaris-QCI/Quantum-Computing-and-Information-ed2/blob/main/Qiskit/13-Quantum-Error-Correction/3-qubit-phaseflip-demo.ipynb)

### 9-qubit-Shor-code-demo

[![Open In Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Polaris-QCI/Quantum-Computing-and-Information-ed2/main?labpath=Qiskit%2F13-Quantum-Error-Correction%2F9-qubit-Shor-code-demo.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polaris-QCI/Quantum-Computing-and-Information-ed2/blob/main/Qiskit/13-Quantum-Error-Correction/9-qubit-Shor-code-demo.ipynb)
