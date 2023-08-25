# Smart Sensor Data Analysis
This project predicts appliance's currently running service using power consumption only, with a minimal example of an Esspresso Machine

## Getting started
This is to show how to install and run the project on your local machine.

## Dependencies
The first thing that needs to be installed is anaconda. The platfrom in which python runs on. You can use this link to install it.
https://conda.io/docs/user-guide/install/index.html
and also you need to install python3.6 from here 
https://www.python.org/downloads/
and pip from here
https://pip.pypa.io/en/stable/installing/
right now you need to create an anaonda environment in which you will install the dependencies on which can be done using this command

Then you need to install keras, the machine learning library in python
```
conda install -c conda-forge keras 
```
Then you need the database application for this project which is in our case influxdb. You need to install it using these commands.
```
$ pip install influxdb
$ pip install --upgrade influxdb
```
you also need theano backend for keras from here
http://deeplearning.net/software/theano/install.html

There are some more dependencies to download from these commands:
```
pip install import-ipynb
conda install -c msys2 m2w64-toolchain 
conda install -c anaconda mkl-service 
conda install -c conda-forge blas 
```
you should also have jupyter notebook which is the IDE for python in this environment and you should get it by only installing anaconda.

## Run

To run the code you have to activate the environment you have created earlier. Using this command.
```
activate Nameofyourenvironment
```
then you go to the directory of the project run jupyter
```
jupyter notebook
```
