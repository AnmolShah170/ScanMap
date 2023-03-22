# ScanMap
## A Multi-threaded Python Port Scanner for use on Linux or Windows
ScanMap is a script written in Python3 that allows multi-threading port scanning. The program is interactive anf simply requires you to run it to begin. Once started, you will be asked to input an IP Address or a FQDN as ScanMap does resolves hostnames. A full port scan can take as little as 1 seconds, but at max should take less than 1 minute 30 seconds depending on your internet connection.

## Requirements
Python3 must be installed on your system in order to function Pip3 for installation via PyPi repository

## Installation
### Installation via Git
`git clone https://github.com/Anmolshah170/ScanMap.git` #to save the program to your machine, or utilize tha download option

You can add ScanMap to run from any directory by adding a symbolic link:
`sudo ln -s $(pwd)/ScanMap.py /usr/local/bin/ScanMap`
