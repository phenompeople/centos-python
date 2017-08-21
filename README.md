[![Build Status](https://travis-ci.org/phenompeople/centos-python.svg?branch=master)](https://travis-ci.org/phenompeople/centos-python)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Python 

Dockerfiles for building Centos based Python images.

The images are available directly from [phenompeople organization] (https://hub.docker.com/u/phenompeople/)

**Which Python container do i need?**

There are a few minor downsides, such as very slightly worse library support and the fact that some current Linux distributions and Macs are still using 2.x as default (although Python 3 ships with many of them), but as a language Python 3.x is definitely ready.
As long as Python 3.x is installed on your user's computers (which ought to be easy, since many people reading this may only be developing something for themselves or an environment they control) and you're writing things where you know none of the Python 2.x modules are needed, it is an excellent choice.
Also, most Linux distributions have Python 3.x already installed, and all have it available for end-users. Some are phasing out Python 2 as preinstalled default.

### Supported tags and respective Dockerfile links

#### phenompeople/centos-python

[![Docker Automated build](https://img.shields.io/docker/automated/phenompeople/centos-python.svg?style=plastic)](https://hub.docker.com/r/phenompeople/centos-python/)
[![Docker Build Status](https://img.shields.io/docker/build/phenompeople/centos-python.svg?style=plastic)](https://hub.docker.com/r/phenompeople/centos-python/)
[![JDK Docker Pulls](https://img.shields.io/docker/pulls/phenompeople/centos-python.svg?style=plastic)](https://hub.docker.com/r/phenompeople/centos-python/)

* **`latest`		([3.5.2/Dockerfile](https://bitbucket.org/phenompeople/centos-python/src/master/3.5.2/Dockerfile))**
* **`3.5.2` 		([3.5.2/Dockerfile](https://bitbucket.org/phenompeople/centos-python/src/master/3.5.2/Dockerfile))**
* **`2.7.13` 	([2.7.13/Dockerfile](https://bitbucket.org/phenompeople/centos-oraclejava/src/master/2.7.13/Dockerfile))**

#### Pre-Requisites

- install docker-engine [https://docs.docker.com/engine/installation/](https://docs.docker.com/engine/installation/)

## Maintainers

* Rajesh Jonnalagadda (<rajesh.jonnalagadda@phenompeople.com>)

## License and Authors

**License:**	Apache License

**Author :** Phenompeople Pvt Ltd (<admin.squad@phenompeople.com>)