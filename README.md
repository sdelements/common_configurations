# Common Configurations

This repository contains a set of common configurations files that can be re-used for other projects.

Symbolic links can be created to link files to this repository as so: `ln -s path/to/config/file path/to/store/file`

## How to use this repository

Add this repository as a submoule to your project like so:
```
git submodule add https://github.com/sdelements/common_configurations
```

## How to update my repo to use the latest version

From your repository, run the following commands in terminal:
```
git submodule update --remote --recursive
```
