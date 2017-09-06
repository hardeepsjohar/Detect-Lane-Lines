# Detect-Lane-Lines

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road    
that show us where the lanes are act as our constant reference for where to    
steer the vehicle.  Naturally, one of the first things we would like to do    
in developing a self-driving car is to automatically detect lane lines using    
an algorithm.

In this project we will detect lane lines in images using Python and OpenCV.   
OpenCV means "Open-Source Computer Vision", which is a package that has many   
useful tools for analyzing images.  

## Getting Started

1. Confirm Python 3 is active.
2. Open Detect_Lane_Lines.ipynb in a Jupyter Notebook

Jupyter Notebook is an interactive environment for writing and running   
code.

If you do not have Jupyter Notebook installed instructions are here:   
(http://jupyter.readthedocs.io/en/latest/install.html)

It is also recommended to have an Anaconda Environment setup.  You can get  
started here: http://conda.pydata.org/docs

Conda is an open source package management system and environment management    
system for installing multiple versions of software packages and their  
dependencies and switching easily between them. It works on Linux, OS X   
and Windows, and was created for Python programs but can package and distribute  
any software.

Using Anaconda consists of the following:

1. Install [`miniconda`](http://conda.pydata.org/miniconda.html) on your   
computer
2. Create a new `conda` [environment](http://conda.pydata.org/docs/using/envs.html) using this project
3. Each time you wish to work, activate your `conda`environment

More info [here](http://conda.pydata.org/docs/).

python get-pip.py

3. Once you have Anaconda or another Python environment setup an easy way   
to install packages is via pip.  You can get pip via the command line using    
"python get-pip.py"

4. Packges you will need to install to run Detect_Lane_Lines.ipynb are below.   
Run each individually:   

pip install opencv-python   
pip install imageio    
pip install moviepy   

5. Upon completion of all three you are ready to run the first cell.  Run each  
cell in order from the top and the comments will guide you along.


## Authors

* **Hardeep S Johar** - *Initial work* - [HardeepSJohar](https://github.com/hardeepsjohar)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details