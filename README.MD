## Pizza Place is a generic pizza delivery site using Django


### Basic Setup
#### Setting up Virtual Environment 
- See <a href = "https://docs.python.org/3/tutorial/venv.html"> Virtual Environments and Packages </a> in Python documentation for more info
1) Configure  virtual environment called `pp_env` via terminal after setting up application folder & git repo. This creates a new `pp_env` folder which contains the `pyenv.cfg` file
    - `python3 -m venv pp_env`
2) Activate the virtual environment by entering 
    - `source pp_env/bin/activate` (Mac)
    - `pp_env\Scripts\activate.bat` (Windows)
3) The terminal shell prompt should now be preceded with `(pp_env)`    
#### Install Django
- See <a href = "https://docs.python.org/3/installing/index.html#installing-index"> Installing Python Modules</a> for more info
1) Using pip, install Django `from within` the virtual environment prompt
    - `pip install Django`