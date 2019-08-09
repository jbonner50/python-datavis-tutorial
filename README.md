

# python-dojo

### Installing python3 & pip
1. Install **Python 3.6**  
```
MacOS: brew install python3
Windows: use installer from http://python.org and tick the box to include python in your PATH
```
2. After Python installation open a terminal window and confirm you have python3 and pip3 installed on your path. Pip is a tool that allows you to install and manage additional libraries and dependencies that are not distributed as part of the standard library.
```
$ python3 --version
Python 3.6.3
$ pip3 --version
pip 9.0.1 from /usr/local/lib/python3.6/site-packages (python 3.6)
```
Note: If **python3** is not found try just **python** instead.  Most OSs support both python2 and python3 installations but if python3 is the only python on the system it may be using the **python** alias.  If **python --version** and **pip --version** both report 'Python 3.x' then proceed using the commands 'python' and 'pip' instead of 'python3' and 'pip3'.

### Installing Jupyter Notebook
Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.
1. Ensure that you have the latest pip; older versions may have trouble with some dependencies:
```sh
$ pip3 install --upgrade pip
```
2. Then install the Jupyter Notebook using:
```sh
$ pip3 install jupyter
```
### Running the Notebook
After you have installed the Jupyter Notebook on your computer, you are ready to run the notebook server.
1. Start the notebook server from the command line:
```sh
$ jupyter notebook
```
2. This will print some information about the notebook server in your terminal, including the URL of the web application (by default, http://localhost:8888):
```
> [I 08:58:24.417 NotebookApp] Serving notebooks from local directory: /Users/{SSO}
> [I 08:58:24.417 NotebookApp] 0 active kernels
> [I 08:58:24.417 NotebookApp] The Jupyter Notebook is running at: http://localhost:8888/
> [I 08:58:24.417 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
```
4. You should see the notebook open in your browser.

When the notebook opens in your browser, you will see the Notebook Dashboard, which will show a list of the notebooks, files, and sub-directories in the directory where the notebook server was started.

![Notebook Dashboard](https://jupyter.readthedocs.io/en/latest/_images/tryjupyter_file.png)

### Installing Python Modules
In the exact same way we installed Jupyter Notebooks using pip, we will install other modules we will need throughout this dojo:

- **NumPy** - adds support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- **Pandas** - offers data structures and operations for manipulating numerical tables and time series
- **Matplotlib** - used to embed plots into applications like Jupyter Notebooks

```sh
$ pip3 install numpy
$ pip3 install pandas
$ pip3 install matplotlib
```
