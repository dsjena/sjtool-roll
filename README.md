# Introduction to sjtool-roll
 
 This is a for the roll sjtool prepared to be installed in the eHPC
 
 Prepared by: S. Jena
 
## Overview 
 
## Requirements

## Dependencies
 
## Building

To build the python-roll, execute this on a Rocks development machine (e.g., a frontend or development appliance):
```
# ROLLNAME=python ./bootstrap.sh 2>&1 | tee bootstrap.log
# make 2>&1 | tee build.log
```
A successful build will create the file *.iso


 
## Installation
 

To install, execute these instructions on a Rocks frontend:
```
# rocks add roll *.iso
# rocks enable roll ${1}
# cd /export/rocks/install
# rocks create distro
```

## Testing
 
