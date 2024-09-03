# Getting started

## Dowload the source code

You can download the source code from my [GitHub repository](https://github.com/RodrigoAnciaes/Linguagem_Autoral_Aqua_Logcomp.git).

## Folder structure

The project is organized as follows:

```
.
├── docs
│
├── Compiler
|
├── FlexBisonV2

```

* The `docs` folder contains the documentation of the project.
* The `Compiler` folder contains the source code of the compiler. The most recent version, uses a python written lexical and syntactic analyzer instead of the flex and bison tools.
* The `FlexBisonV2` folder contains the source code of the lexical and syntactic analyzers, that besides being complete, still have no integration with the rest of the compiler.

## Compiling the code

Each folder contains in its respective README file the instructions for compiling the code.

In order to use the compiler, the only requirement is to have python installed on your machine.

For the lexical and syntactic analyzers, you will need to have gcc, flex and bison installed on your machine.