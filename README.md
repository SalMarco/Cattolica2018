# Empirical Research Python Lab

## Prerequisites

The course will be focused on an introduction to Python with focus to data analysis and machine learning.

The two main tolls will be:
  - **Jupyter:** interactive notebook for Python and others language
  - **Git:** repository system [wiki page](https://en.wikipedia.org/wiki/Git)

### Install git

  - **For Window user:** download git from https://gitforwindows.org/. During the installation select **use git bash only** in the relative step, leave the rest like it is.
  - **For Unix/Mac users:** git should be already available in the terminal.

I invite you to create and account on [GitHub](https://github.com/) or [GitLab](https://gitlab.com/users/sign_in) and start to using it following some guide like:
  - http://kbroman.org/github_tutorial/pages/init.html
  - http://rogerdudler.github.io/git-guide/

### Install Anaconda

One the easiest way to have Python and Jupyter is via Anaconda.

From the site download the version for **Python 3.6**:

https://www.anaconda.com/download/

You can find a guide for Jupyter here: [Jupyter Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook).

### Add R Kernel to Jupyter (Optional)

If you want try to use R in Jupyter follow the instruction in the following link.

https://www.datacamp.com/community/blog/jupyter-notebook-r#gs.z0gxLNc

**NOTE** Sometimes for some Windows users can be difficult. If you run in some problems try the following:

https://stackoverflow.com/questions/44056164/jupyter-client-has-to-be-installed-but-jupyter-kernelspec-version-exited-wit

In any case it is not mandatory for the course and we can address any problems later.


## How to clone the repository with all the lessons

All the files for all the lessons are in a repository: [Cattolica2018 Repo](https://github.com/SalMarco/Cattolica2018).

The repository has pointer to one dedicated repository for each lesson.

The steps to follow to clone and update s repository on your pc are listed below.

### Open the terminal

For **Mac/Linux** just open the terminal

For **Windows** start `git bash`.  

### Select a destination for the repository

You can see the path of the folder you are in with `pwd` (i.e. print working dir). At the beginning you should be in your home folder.

You can list all the files/folder with `ls -lrt`. The most recent files/folders will be at the bottom.

You can change the directory you are in with `cd $folderName`.

If you use only `cd` you will return to your home folder.

With `cd ..` you will return **one** step back in the folders tree.


### Clone all the repos together
In order to clone the `Cattolica2018` repository with all the others already inside execute

`git clone --recursive git@github.com:SalMarco/Cattolica2018.git`

In order to update in one time the `Cattolica2018` repository and all the others, from inside the folder, execute

`git submodule update --recursive --remote`.  

### Clone the repo of a specific lesson

If you want to clone the repository on **only** one lesson execute

`git clone $urlOfTheSpecificLesson`

In order to update the repository, from inside de folder, execute

`git clone origin master`
