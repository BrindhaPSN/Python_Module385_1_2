# Creating a virtual environment (venv)
1. Create your project folder and make sure your terminal is at the root of the project
2. To create virtual env, run in terminal `python3 -m venv venvname`

# using a virtual env
- If you dont activate your virtual env, when you install packages they won't be env specific
- To activate in mac: `source venvname/bin/activate`
- To activate in windows: `venvname/bin/activate`
- To deactivate `deactivate`

# Github with venv
- Not all files should be pushed to github
- create a `.gitignore` file
- list all the folders to be ignored by github(venv folder-venv name(ex:labenv))

# To save the list of installed packages:
- Run command `pip freeze > requirements.txt`
- creates requirements.txt file with all required packages for this program.