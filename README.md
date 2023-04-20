# Quick-start
Some fundamental tutorial for Python, GitHub, and command line, etc.

### Python tutorials for beginners

https://www.runoob.com/python3/python3-tutorial.html

https://thepythonguru.com/

https://www.codecademy.com/learn/learn-python-3

### Anaconda

Learn how to use Anaconda to install Python on your computer and how to install new packages.

https://conda.io/projects/conda/en/latest/user-guide/getting-started.html

### Jupyter Notebook

Web-based interactive development environment for notebooks,code,and data.

https://docs.jupyter.org/en/latest/start/index.html

## Useful tips for GitHub

1. In the main page of GitHub, typing **'s'**: search.

2. When entering a certain project, the nested files are inconvenient to search. Typing **'t'**，search for all files in this repository.

3. Typing **'command+k'**: Navigation inside the page

4. Click into a file, say XX.py. Typing **'L'**: navigate to a certain line of the file, and you may copy that line.

5. Typing **'b'**: you can find the correction, updates, and all history record of the opened file.

7. Navigate to a specific project, and type the dot symbol **'.'**, it would open a web-based VScode editor and you can run any program on that web.

6. Web-based editor. On the top of the Github website, type:

    
        gitpod.io/#/

infront of the address. With this tool, you don’t need to download the project locally and build the corresponding environment with terminal. The project will be opened in a **web-based editor**, it’s sort of a server and you may use it as your personal laptop. Many popular languages are pre-installed including Python, Java, Go. You can execute some project by typing commands, and check the result in the website.

## How to clone repository from Github

1. First create a local directory where you want to store this library

In my Macbook, I created a directory: GIT_local in Documents, so firstly, cd to the path(Drag this directory into terminal and get the address):

    cd /Users/stephen/Documents/GIT_local

Then, create a directory for the specific project:

    mkdir newproject

Copy the URL of the specific project:

<img width="397" alt="Screenshot 2023-04-18 at 12 11 01" src="https://user-images.githubusercontent.com/98719524/232853094-6387f09d-ba75-4e19-b965-4987791c1ea4.png">


cd to the newproject and type the command: 

    git clone the_copied_URL

When you open the directory again, you'll find that you already have the repository. Then navigate to the repository's address.

### Advanced search with specific conditions: date, programming language, stars, 

https://github.com/search/advanced

### GitHub official manual book

https://docs.github.com/en

### GitHub Copilot 

https://docs.github.com/en/copilot

## Pip

When using Python, you might need to install and use certain packages. And there is a command available for that known as 'pip', it's the standard Python package manager that downloads and installs packages from the Python package index. With pip, you can install, upgrade, and uninstall various Python packages. You'll learn how to use it, and how to handle pip errors.

#### What is the error pip: command not found?

Sometimes when you are installing packages, you might face the error: pip: command not found. This error could be due to the following reasons:

-Pip is not installed.

-Pip is installed, but it is not compatible with the current environment.

(P.S On Linux, you must install the pip package manager separately as it is an independent package. But on Mac, you do not need to install pip manually, as long as you are working with Python 3.x. version)

#### Troubleshooting the error pip: command not found

First, check if pip is installed.

    python3 -m pip --version 


If pip is not installed, you can follow the install steps here for your respective OS: https://pip.pypa.io/en/stable/installation/

Second, upgrade pip to the latest version.

    python -m pip install --upgrade pip
    
    
Third, fix environment issues.

It is possible that you are trying to use the wrong version of pip. For example, **pip3** works for **Python3**, whereas **pip** works only for **Python2.**

You can check your Python version on Linux and Mac like this:

    python --version

## PyPI(Python Package Index) 

Find, install and publish Python packages with the Python Package Index

https://pypi.org/

## 🤔 Some tips for your research path

Get into grad school for science, engineering, math and computer science:

https://matt.might.net/articles/how-to-apply-and-get-in-to-graduate-school-in-science-mathematics-engineering-or-computer-science/

Advice for researchers and students:

https://homes.cs.washington.edu/~mernst/advice/

How to get a great letter of recommendation:

https://matt.might.net/articles/how-to-recommendation-letter/
