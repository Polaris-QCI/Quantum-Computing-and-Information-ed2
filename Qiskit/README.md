# Quantum Computing and Information: A Scaffolding Approach (2nd Edition)

This folder contains [Qiskit](https://www.ibm.com/quantum/qiskit) code samples for the textbook *Quantum Computing and Information: A Scaffolding Approach (2nd Edition)* by Peter Lee, Huiwen Ji, and Ran Cheng.

## Copyright

© John Hurst and Peter Lee, Published by Polaris QCI Publishing.

## Local Setup

The code is in the form of Python Jupyter notebooks.

You can run the code locally, or in the cloud using one of several Jupyter hosting services.

To run the notebooks locally, you need to have Python3 installed on your computer.

Consult the instructions at [python.org](https://www.python.org/) to download and install Python3.

Once you have Python installed, create a [Python virtual environment](https://docs.python.org/3/library/venv.html)
and install the necessary packages in the folder of this repository using these commands:

``` bash
cd Qiskit
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

To run the Jupyter notebook server, use the command:

``` bash
jupyter notebook
```

You can also run the notebooks in [Visual Studio Code](https://code.visualstudio.com/docs/sourcecontrol/github) if you prefer a more powerful coding environment.

## Cloud Services

You can also run the Jupyter notebooks on Google Collab: TODO
