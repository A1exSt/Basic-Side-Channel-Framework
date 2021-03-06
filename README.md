# Basic-Side-Channel-Framework

This repository is aim to provide a basic framework for side-channel analysis. Currently, it combines SAKURA-G, Chipwhispere, OpenADC, Jupyter Notebook...etc. 

![](https://i.imgur.com/iYMUDuA.png)

## Installation

- Installing python and juypyter notebook and the required packages

```
pip install jupyter notebook
pip install configobj
pip install pyqtgraph
```

- Installing FTD2XX driver. To install this package, download a copy of the ftd2xx repository and unzip it somewhere. Then run the following where you unzipped it:

```
python setup.py install
```

- Clonning the latest version of framework
```
git@github.com:phonchi/Basic-Side-Channel-Fraewwork.git
```

- Clonning either the maintaining version of star group
```
git@github.com:phonchi/chipwhisperer.git
```

or the official chipwhisperer

```
git@github.com:newaetech/chipwhisperer.git
```

- Installing the chipwhisperer
```
cd c:\chipwhisperer\openadc\controlsw\python
python setup.py develop
cd c:\chipwhisperer\software
python setup.py develop
```
- You can also access the latest build through docker
https://hub.docker.com/r/phonchi/chipwhisperer-docker/

- Follow the wiki page or the SAKURAG manual to do a quick capture, and save the results as raw states
- Now you can manipulate the trace like http://nbviewer.jupyter.org/github/phonchi/chipwhisperer/blob/master/testchip.ipynb



## Development
- Use Tools/make_ise to manage your projects
- The samples project for target control hardware are in the Target_Hardware folder
- More detail can be found in the wiki page
