# Shell script to create Django project from scratch

#Linux

With this script it is possible to create a Django project from scratch.

When starting it is necessary to indicate:

	* The name of the project
	* The Python version
	* The Django version

Warning:

	* Change line 25 with the path to the folder where you save Django projects.
	* Change the list of libraries needed for the project on line 28.

This script does the following:

	* Ask for the project name, the Python version and the Django version.
	* Create the folder with the project name inside the folder (indicated in line 25 PROJECTS_FOLDER = ...).
	* Create and activate the virtual environment (virtualenv) as the name '.venv'.
	* Update the 'pip' and 'setuptools'.
	* Install Django.
	* Install the necessary libraries for the project (indicated in the list on line 28).
	* Create the Django project.

	* Create the base app
	* Create the folders:
		templates
			templates / base
		static
			static / base
				static / base / css
				static / base / js
				static / base / images

	* Create the main app
	* Create the folders:
		templates
			templates / main
	* creates the urls.py file

	* Create the 'requirements.txt' file
	* Create the '.env' file for use with the django-decouple library that allows you to remove sensitive and confidential data from settings.py.
	* Create the '.env.example' file to send as an example to the repository on GitHub.
	* Create the '.gitignore' file
	* Create the 'LICENSE' file with the MIT license.
	* Create the 'README.md' file.
	* Initialize empty GIT repository.


Instructions for Python Decouple: https://pypi.org/project/python-decouple/

The creation of this script was inspired by Regis Santos https://gist.github.com/rg3915 and her script https://gist.github.com/rg3915



