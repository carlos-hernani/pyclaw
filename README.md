# pyclaw
 Examples usign PyClaw

# Installation


## For Linux Users

`sudo apt install gfortran`

`python3 -m venv .venv`
`. .venv/bin/activate`
`pip install --upgrade pip`
`pip install matplotlib clawpack scipy`

## For OS X Users

Using the [Docker for Clawpack](http://www.clawpack.org/docker_image.html) Guide.

Or compiling from source:

`git clone git://github.com/clawpack/clawpack.git`
`cd clawpack`
`brew install gcc` to install `gfortran`
`python setup.py config_fc --fcompiler=gfortran install`
`pip install scipy`

