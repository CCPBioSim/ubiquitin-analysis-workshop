# CCPBioSim Ubiquitin Analysis Workshop

[![build](https://github.com/ccpbiosim/ubiquitin-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main)](https://github.com/ccpbiosim/ubiquitin-analysis-workshop/actions/workflows/build.yaml)

This workshop illustrates the application of a number of Python-based tools to the analysis of the results from a short (1 nanosecond) simulation of ubiquitin, investigating the question "how similar is the MD trajectory to the crystal and NMR structures?"

The workshop illustrates:
1. The use of the Python MDTraj module (see http://www.mdtraj.org)
2. The use of the Python matplotlib module for plotting (see http://www.matplotlib.org)
3. The use of the Python MDPlus module for Principal Component Analysis (see http://bitbucket.org/claughton/mdplus)

## Docker

This container is derived from the CCPBioSim JupyterHub base image. This container
adds the necessary software packages and notebook content to form a deployable
course container.

## How to Use

In our containers we are using the JupyterHub default port 8888, so you should
forward this port when deploying locally::

    docker run -p 8888:8888 ghcr.io/ccpbiosim/ubiquitin-analysis-workshop:latest

## Contact
Please direct all comments and queries to [Charlie Laughton](mailto:charles.laughton@nottingham.ac.uk)

