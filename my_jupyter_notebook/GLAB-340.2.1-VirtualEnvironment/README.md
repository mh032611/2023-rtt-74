[![Per Scholas](per_scholas_logo.png)](https://www.perscholas.org) 

# GLAB-340.2.1-VirtualEnvironment

## Introduction
Create Virtual Environment using venv, virtualenv and conda modules

## Lab Overview
In this lab, we'll demonstrate how to create virtual environment. Learner should be able to create and activate virtual envrironment using venv, virtualenv and conda module by the end of this lab.

## Examples
### Example 1: How to create and activate a virtual environment in Python using venv module

First, open your command prompt or terminal and navigate to the directory where you want to create the virtual environment.

Next, create a new virtual environment by running the following command:

```
python -m venv myenv
```

This will create a new directory named myenv that contains the virtual environment.

Activate the virtual environment by running the appropriate command for your operating system:

On Windows:

```
myenv\Scripts\activate
```
On Linux or macOS:
```
source myenv/bin/activate
```
This will activate the virtual environment and you will see its name displayed in your command prompt or terminal.

You can now install any required packages or dependencies within this virtual environment using pip. For example:

```
pip install pandas
```

## Example 2: How to create and activate a virtual environment in Python using virtualenv module

Open a command prompt or terminal window.

Navigate to the directory where you want to create the virtual environment.

Enter the command virtualenv myenv, replacing "myenv" with the name you want to give your virtual environment.

Activate the virtual environment by entering the command 

```
source myenv/bin/activate
```
on Mac/Linux or 

```
myenv\Scripts\activate.bat
```
on Windows.

## Example 3: How to create and activate a virtual environment in Python using conda module

Open a command prompt or terminal window.

Enter the command 

```
conda create --name myenv
```
replacing "myenv" with the name you want to give your virtual environment.


Activate the virtual environment by entering the command 
```
conda activate myenv
```

To deactivate the virtual environment, enter the command 

```
conda deactivate myenv
```

That's it! You should now have a virtual environment set up and ready to use.
