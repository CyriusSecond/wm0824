# wm0824
WM0824TU Economics of Cyber Security (2020)

### Rules of Conduct
- **IMPORTANT** Use PEP8 style convention. [PEP8 Guidelines](https://www.python.org/dev/peps/pep-0008/)
- Do **NOT** add any big data sets to the repository.
- Do **NOT** work on the **master** branch. 
- Do **NOT** add binary/compiled code to the repository. (Unless some very specific library) 
- Every new feature should be developed on its own branch. 
- Document your code. 
- Use meaningful variable names. 
- Add descriptive comments to the commits.

### How to use PIPENV
- Install the library: `pip install pipenv`
- Add **PIPENV_VENV_IN_PROJECT** in your environmental variables and set the value to **true**.
- Go inside the project folder and open a new **CMD** window. 
- Type `pipenv install`
- A **.venv/** folder should appear in the repository.
- Type `pipenv shell` to activate the environment.
- **IMPORTANT!** To install libraries in the pipenv use the following command: `pipenv install [package_name]`. In this way we can guarantee that all the necessary libaries will be available when somebody will recreate the environment. 
- Do **NOT** use `pip install [package_name]`, instead use `pipenv install [package_name]`. Make sure you are in the repository/project folder when you type the command.