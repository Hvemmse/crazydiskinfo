# CrazyDiskInfo (forked bug fixed version)
![image](https://user-images.githubusercontent.com/32232575/151078336-b265c576-40c6-46ae-8860-5c5edba09e36.png)
![image](https://user-images.githubusercontent.com/32232575/151077417-f466a556-b543-44bb-8c6b-79f978920794.png)

## Introduction
CrazyDiskInfo is an interactive TUI S.M.A.R.T viewer for Unix systems.
This forked version includes some bug fixes.

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
