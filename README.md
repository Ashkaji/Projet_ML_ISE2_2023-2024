Step-by-step guide on how to use Jupyter in your local Python environment:

1. **Create a virtual environment**: Navigate to the directory where you want to create your project and run the following command to create a virtual environment¹.
    ```python
    python -m venv venv
    ```
2. **Activate the virtual environment**: Now, activate the virtual environment¹.
    ```python
    venv\Scripts\activate
    ```
3. **Install Jupyter Notebook**: Install Jupyter Notebook in your virtual environment¹.
    ```python
    pip install jupyter
    ```
4. **Install IPython**: Install IPython, which provides the IPython kernel for Jupyter¹.
    ```python
    pip install ipython
    ```
5. **Install Jupyter kernel for the virtual environment**: Run the following command to create a kernel that can be used to run Jupyter notebook commands inside the virtual environment¹.
    ```python
    ipython kernel install --user --name=venv
    ```
6. **Select the installed kernel when you want to use Jupyter notebook in this virtual environment**: Run `jupyter notebook` command in the command prompt or Powershell and the Jupyter environment will open up. Click on the kernel and click change kernel, you will be able to see the kernel you just created¹.

Remember, after you are done with the project and no longer need the kernel, you can uninstall it by running the following code¹:
```python
jupyter-kernelspec uninstall venv
```

Source : conversation avec Bing, 2/6/2024
- (1) Using Jupyter Notebook in Virtual Environment - GeeksforGeeks. https://www.geeksforgeeks.org/using-jupyter-notebook-in-virtual-environment/.
- (2) How to use Jupyter notebooks in a conda environment?. https://stackoverflow.com/questions/58068818/how-to-use-jupyter-notebooks-in-a-conda-environment.
- (3) Using Virtual Environments in Jupyter Notebook and Python. https://janakiev.com/blog/jupyter-virtual-envs/.
- (4) How to use Python Virtual Environments in Jupyter Notebook. https://markbyrne.us/using-python-virtual-environments-in-jupyter-notebook/.
- (5) python - Using virtualenv on Jupyter Notebook - Stack Overflow. https://stackoverflow.com/questions/55448244/using-virtualenv-on-jupyter-notebook.
