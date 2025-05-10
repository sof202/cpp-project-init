# cpp-project-init

Simple helper script to make all of the files/directories that I might want to
build a C++ project. Comes equipped with:

- clangd files
    - Detailing my general preferences (linting, variable naming, formatting
    *etc.*)
- Make/CMake build files
    - Simply use `make` to build the target (executable will go into
    `\build\bin\`)
- A simple entry point will be created (just prints the name of the project)

This also initialises the git repository for you (doesn't commit anything).

## How to install

```
git clone git@github.com:sof202/cpp-project-init.git
cd cpp-project-init
ln -s $PWD/cpp-project-init $HOME/.local/bin/ # Or somewhere else on your path
```

## How to use

```
cpp-project-init myProject # "project_name" is used if no argument is given
```
