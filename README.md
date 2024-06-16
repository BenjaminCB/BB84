# BB84
A jupyter notebook containing a BB84 implementation for my QIC course mini-project.

# How to run
## Install venv
First, you need to install the venv module using pip. Open your terminal or command prompt and run the following command:

```
pip install virtualenv
```

## Create a virtual environment
Navigate to the directory where you want to create your virtual environment. Then, run the following commands based on your operating system:

**Windows**:

```
python -m venv myenv
```

**MacOS/Linux**:

```
python3 -m venv myenv
```

This command creates a directory named myenv that contains the virtual environment.

## Activate the Virtual Environment
After creating the virtual environment, you need to activate it.

**Windows**:

Open Command Prompt and run:

```
myenv\Scripts\activate
```

**MacOS/Linux**:

Open your terminal and run:

```
source myenv/bin/activate
```

Once activated, your command prompt will change to show the name of the active environment (e.g., (myenv)).

# Install Packages from requirements.txt
To install the packages listed in requirements.txt, run the following command:

```
pip install -r requirements.txt
```

## Opening jupyter
To open the jupyter notebook run the following command:

```
jupyter notebook
```

This should startup a local jupyter notebook, from which you can open and run the bb84 notebook.
