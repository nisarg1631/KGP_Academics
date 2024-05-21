# KGP ACADEMICS

A repository of all academic materials from my time in the Department of Computer Science and Engineering [2019-2024] at Indian Institute of Technology, Kharagpur.

It contains the yearwise repositories and other lab/project repositories as submodules.

By default if you clone this repository all subdirectories will be empty. To list all the submodules run 
```
git submodule status
```
To fetch a specific submodule run 
```
git submodule update --init <submodule_name>
```
e.g., 
```
git submodule update --init Repositories/COA_LAB_AUTUMN_2021
git submodule update --init Third_Year
```
To fetch all submodules run (note that this can take a very long time)
```
git submodule update --init --recursive
```
You can also clone the individual repositories directly from GitHub.