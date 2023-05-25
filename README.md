# C++ in OpenShift Dev Spaces 3.5.0+

This is a basic repo to demonstrate running a sample C++ applications in OpenShift Dev Spaces 3.5+.

As of OpenShift DevSpaces 3.3, Openshidt Dev Spaces support three browser based IDEs
1. __MS Visual Studio Code__ >> che-incubator/che-code/insiders
1. JetBrain IntelliJ IDEA >>  che-incubator/che-idea/latest
1. Eclipse Theai >> che-incubator/che-theia/latest


The sample Devfile load the sample code and all you need to get started to compile the code.

:exclamation: This is a sample repository, that could be clone as a starting base for any c++ project


## Loading the workspace in OpenShift Dev Spaces

* With `Vs Code` use:
    > https://github.com/froberge/devspaces-cplus-plus

* With IntelliJ
    > https://github.com/froberge/devspaces-cplus-plus?che-editor=che-incubator/che-idea/latest

## Execute the code.

To execute the file fom a terminal.

### Compile
```
g++ -o Test main.cpp
```

### RUN

```
./Test
```

## Interacting with git.

Once the files is load from GitHub. Enter the next to line into a terminal.

> git config  user.name "[YOUR NAME]"

> git config  user.name "[YOUR EMAIL]"
