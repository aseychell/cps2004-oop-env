# CPS 2004 - Object Oriented Programming

University of Malta

Author: Aldrin Seychell

## Overview

This environment is based on docker with Ubuntu 16.04 as the base image.
This docker image adds c++ compiler g++ with standard libraries. 
For Java, this docker image consists of the OpenJDK version 8 JDK distribution.  It also sets the necessary JAVA_HOME
environment.


## Installation Instructions

1. Install docker
2. Make sure you share your hard drive with docker (check your docker settings)
3. Execute `docker run --rm -it -v C:/dev/trees/cpp:/project cps2004-oopenv`, replacing "C:/dev/trees/cpp" with the directory you want to work in.
4. To make sure everything is setup correctly, execute `g++ --version`, `java -version` and`javac -version`
5. Practice, Practice, Practice in both C++ and Java.
