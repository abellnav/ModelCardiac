# ModelFLOWs-Cardiac
Welcome to the ModelFLOWs-Cardiac repository!

Code updated soon...

## Table of contents
* [About ModelFLOWs-Cardiac](#about-Modelflows-cardiac)
* [Versions](#versions)
* [Requirements](#requirements)
* [Setup](#setup)
* [Run](#run)
* [More info](#more-info)

## About ModelFLOWs-Cardiac
ModelFLOWs-Cardiac is an open source Software for analysis of echocardiography images using modal decomposition and deep learning architectures. It constitutes part of the ModelFLOWs-app [ModelFLOWs-app repository](https://github.com/modelflows/ModelFLOWs-app).

## Versions
The version currently available is the ModelFLOWs-Cardiac desktop version.
	
## Requirements
ModelFLOWs-Cardiac has been developed with:
* Python: 3.10

Other relevant libraries that require installation:
* tensorflow: 2.13.0
* scikit-learn: 1.3.0
* scipy: 1.11.1
	
## Setup
There are two ways to install all required libraries:

#### Option 1. Install all libraries:
```
$ cd ../ModelFlows-Cardiac
$ sudo pip install -r Requirements.txt
```

#### Option 2. Install each library individually:
```
$ cd ../Desktop
$ sudo pip install **insert library name**
```

## Run
To open ModelFLOWs-Cardiac, run the following command:

#### For the desktop version:
Training:
```
$ cd ../ModelFlows-Cardiac
$ python demo_train.py
```
Testing:

```
$ cd ../ModelFlows-Cardiac
$ python demo_test.py
```

## More info
For more information please visit [ModelFLOWs-app's official website](https://modelflows.github.io/modelflowsapp/).
