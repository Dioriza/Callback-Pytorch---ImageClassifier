# Callback-Pytorch-ImageClassifier
Use Callback on pytorch for image recognition datasets for classification.

#Install Miniconda/Anaconda
### **Windows user**
- Download miniconda for Python 3.7
    - please click this link to generate download: [Miniconda Windows 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe)
    - No need to download Miniconda if Anaconda is available.

- Install miniconda
    - When there is a choice for`install for`, choose `Just Me (recommended)`
    - for `Advanced Options`, you can checklist in `Register Anaconda as my default Python 3.7`
    - wait until installation progress is end.

- Run it `Anaconda Prompt`

### **Mac user**
- Download miniconda for Python 3.7
    - please click this link to generate download: [Miniconda Mac OS X 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.pkg)
    - No need to download Miniconda if Anaconda is available.

- Install miniconda

    - Install without changing any options
    - Wait until the installation is complete

- Run it terminal

### **Linux user**
- Download miniconda for Python 3.7
    - please click this link to generate download: [Miniconda Linux 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh)
    - No need to download Miniconda if Anaconda is available.
    
- Install miniconda
    - Run it terminal
    - Install miniconda with this command
        ```
        bash Miniconda3-latest-Linux-x86_64.sh
        ```
    - Write `yes` for agree with that licence, then write `yes` for `prepend miniconda install location to PATH`
    - Wait until the installation is complete

#Setup Environment
create a new directory to wrap the dataset

Select the directory folder for environment placement
```
$ cd 'name of folder'
```
example:
```
$ cd "deep_learning"
```
create environment
```
$ conda env create -f env_jcop.yml
```
open jupyter notebook
```
$ jupyter notebook
```
