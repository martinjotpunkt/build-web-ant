# Buildscript #


## Introduction ##


## How to use ##


## How to extend ##

When implementing new features and modules there are a few things to keep in mind to keep the style in throughout the whole project.

- Implement a facade target in build.xml that depends on the newly implemented target
- Prefix the name of build-files with a hyphen so they cannot be used standalone
- Extract all values (e.g. paths) and define them as properties in the appropriate property-file



## To be done ##

