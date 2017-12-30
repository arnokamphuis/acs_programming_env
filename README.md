# ACS Programming Environment
The base repository for software development during the Applied Computer Science curriculum of the Utrecht University of Applied Sciences.

# Cloning the repository
Cloning the repository requires the submodules to be initialized. Please use the following command to clone the repository:

```
  git clone --recurse-submodules https://github.com/arnokamphuis/acs_programming_env
```

# Updating the submodules
Because some of the submodules have submodules themselves we need to update the submodules using the recursive command option.

```
  git submodule update --init --recursive
```
