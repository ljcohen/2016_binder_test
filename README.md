# 2016_binder_test

To create a Docker container of this repo (uses [Kubernetes](http://kubernetes.io/)), go to [mybinder](http://mybinder.org) and paste the url of this repo: 

(Make sure to use the github url, not the clone.)

https://github.com/ljcohen/2016_binder_test

This will build a binder instance. For example (click on link below):

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/ljcohen/2016_binder_test)

Since a Docker image is created for this repo, this link can be given to people (e.g. a class of students) to all run an identical copy of the repo. The repo may contain data files, which people can then interact with an active Jupyter notebooks. New Jupyter notebooks can be created once the binder instance starts. Alternatively, an existing Jupyter notebook ([index.ipynb](https://github.com/ljcohen/2016_binder_test/blob/master/index.ipynb) can be included within the repo, which will start automatically when someone launches the binder instance. 

Packages can be installed using the terminal, e.g. `pip install screed`. The terminal can be reached from the main Jupyter screen from the right-hand side, under 'New', 'Terminal'. To get to this main screen from a running notebook, click on 'File', 'Open'.

http://mybinder.org/
