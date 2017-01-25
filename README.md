# CrazyDiskInfo
![](http://raw.github.com/wiki/otakuto/CrazyDiskInfo/images/0.png)

## Introduction
CrazyDiskInfo is an interactive TUI S.M.A.R.T viewer for Unix systems.

## Features
* UI similar to CrystalDiskInfo.
* Health and temperature checking algorithms based on CrystalDiskInfo.

## Required libraries
* ncurses
* libatasmart

#### Debian(or derivative) Systems
```
# apt-get install libatasmart-dev libncurses5-dev libncursesw5-dev
```

## Build and Run
```
$ mkdir build
$ cd build
$ cmake ..
$ make && make install
$ sudo crazy
```
