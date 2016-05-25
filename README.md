# Timing lectures #

This is a work-in-progress repository of my [timing lectures](http://www.matteobachetti.it/Varie/Timing).

Lectures follow an iPython notebook where I give the relevant "vocabulary" and I explain the concepts by simulating and analyzing data. This iPython notebook can be downloaded and students can play around with it, inspecting, modifying and re-running all the code in order to get a better grip on the concepts explained in the lectures.

## Install requirements and download
First of all, install Python and iPython.
There are many ways to do it in each architecture. One possible easy way to get up and running quickly with Python is to [follow the instructions here](http://ipython.org/install.html).

The presentation and all material in this "Timing lectures" web page is maintained as a git repository, so first of all [install git](http://git-scm.com). On Unix-like machines, this is very simple. It is generally just a matter of 
```
#!console
$ sudo packagemanager install git
```
where _packagemanager_ can be apt-get, yum, fink, brew, port, or whatever package manager you use in your machine.

Then clone the repository with
```
#!console
$ git clone git@bitbucket.org:mbachett/timing-lectures.git
```
# Run
Go to the directory timing-lectures you just downloaded, then run
```
#!console
$ ipython notebook
```
This will open a web browser page like this:
![ipython.png](https://bitbucket.org/repo/b94zee/images/3595932949-ipython.png)

Just click on 'Pulsar_Timing.ipynb'. This will open the notebook:
![psr_timing.png](https://bitbucket.org/repo/b94zee/images/2319905682-psr_timing.png)

From here you can change all the code and make experiments. You can still run the notebook as a presentation by giving the following command in your terminal:
```
#!console
$ ipython nbconvert Pulsar_Timing.ipynb --to slides --config slides_config.py --post serve
```
