# Make openstack instance
1. Add the following lines to `/bash_profile':
```
export PS1="\u@\h \w> "
alias la="ls -lath"
```
1. Install emacs: `sudo yum install emacs`
1. Install wget: `sudo yum install wget`
1. Download miniconda: `wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh`
1. chmod the download: `chmod +x Miniconda3-latest-Linux-x86_64.sh`
1. Install miniconda: `./Miniconda3-latest-Linux-x86_64.sh`
1. After, append the paths to `.bash_profile`.
1.


# In Openstack instance
1. Go to your instance at [https://openhouse.corp.yahoo.com/project/](https://openhouse.corp.yahoo.com/project/).
1. ssh to the instance: `ssh noteddevoted.corp.ne1.yahoo.com`
1. Install virtualenv: `pip install virtualenv` (taken from [here](http://docs.python-guide.org/en/latest/dev/virtualenvs/))
1. Make a folder project:


## pipenv (?)
1. After installing `python` intall pipenv: `pip install --user pipenv` (taken from [here](http://docs.python-guide.org/en/latest/dev/virtualenvs/))




# Grid Python 3
Install according to Udacity
machine: `dot@gwbl191n01`
folder /tmp/dot/

Based on CarND [Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)
Do the [Configure and Manage Your Environment with Anaconda](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md).

1. Install miniconda. Download the 64bit [installer](https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh).

