# JQXXXX

## Github Usage Guide
Welcome to the Qishi Machine Learning Advanced Study Group! 

Here we will briefly introduce the basic usage of this Github repository.

* Everyone should create a folder using his/her initials (in lower cases) under the `JQXXXX/kaggle/modelers/` folder. (For example: `tx` for Tianyi Xia.) 
* At the beginning of the studying phase, **one should only add code/make changes to one's own folder.** Later on, we will create a shared folder for running & submitting solutions.
* It is always a good practice to first create a branch and make changes on one's local branch. After you think the changes will be bug-free, you can push the branch to the master.
* To Be Continued...

**To get started, we will demonstrate an example here to your name to `JQXXXX/kaggle/collaborators.txt`**

1. First, download this repo to your local machine. You can choose to use either command-line-interface (CLI) or third-party repo management apps (such as GitHub Desktop or SourceTree).
2. 



## Python Virtual Environment Install Guide

Please make sure you've installed `Python 2.7` on your machine. It's a good practice to have a separate virtual environment of Python for this project, to make sure everyone will be using the version of modules for development.

Here, we will follow the [virtualenv guide](http://docs.python-guide.org/en/latest/dev/virtualenvs/) to build our local environment. To install `virtualenv`, do:

```bash
$ pip install virtualenv
```

After that, make sure are at the root directory of the Qishi Kaggle folder (say `../JQXXXX/kaggle/`). Then do the following:

```bash
$ virtualenv -p /usr/bin/python2.7 env # this will create  a new folder called env under ../JQXXXX/kaggle/
$ source env/bin/activate # this will activate the local python2.7 
$ pip install -r requirement.txt # this will install all the required packages
```

To deactivate the virtual environment, please type:

```
$ deactivate
```



