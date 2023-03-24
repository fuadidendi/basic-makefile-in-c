# basic-makefile-in-c
<div id="badges" align="left">
    <a href="https://medium.com/@hazikfuadidendi/basic-makefile-in-c-c-programming-d63518afeeb1">
        <img src="https://img.shields.io/badge/medium-basicmakefile-brigthgreen"/>
    </a>
</div>

Basic makefile in C, compile C codes using make.
In this project uses C programming language and Makefile as a way to build the project. This project was tested both on Windows and Linux Operating System.

## About the Project
Simple example how to use makefile to build C source code.


## Getting Started
Clone this repository, setup, and then run.

### Clone
For clone this project
```shell
$ git clone https://github.com/fuadidendi/basic-makefile-in-c.git
```
### Setup
#### Installation on Windows
If you are running in Windows system, make sure you have installed the make tools (e.x. MinGW, Cygwin, CMake).

#### Installation on Linux
Just make sure there is make tools in your linux system. You can check your make tools by check the version.
```shell
$ make --version
```
## Usage
### Make only
This will only compile the source
```shell
$ make
```
### Clean the compiled file
This will clean the compiled file
```shell
$ make clean
```
### Make and run
This will compile the source and then run the output file
```shell
make run
```