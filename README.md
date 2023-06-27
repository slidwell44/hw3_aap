# hw3_aap

Information on using this cookiecutter

Development workflows
=======================

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:slidwell44/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named hw3_aap, then do;

```bash
git remote add origin git@github.com:slidwell44/hw3_aap.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── hw3_aap	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
		│
		├───data						<- Final and intermediate data
		│   └───raw						<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		└───output
				readme.md				<- Guidance for using this folder


Documentation
--------------

In this very simple project structure template, we've just included a markdown file with some typical
section headings to use for project notes. Expand as desired. Later in the semester we will learn how to
use Sphinx with restructuredText to write and generate documentation.

#-------------------------------------

In hw3_aap_main.ipynb I create a a tool that can web scrape data and turn that data into a pandas dataframe. Then I do plotting on the data using Plotly, ipywidgets, Bokeh, and seaborn.
I try to compare the different plotting tools throughout my code and find which one is best overall.

I created the version control in my personal github and did all the pushes through the bash terminal.