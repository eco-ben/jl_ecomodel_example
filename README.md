# Julia presentation for UQ CBCS Coding Club

This repository contains code for the presentation and demonstration of Julia
for the CBCS coding club. The presentation covers some basics of Julia,
features of the language and advantages and disadvantages for biological science.

## If you want to follow along the demonstration:

### Install Julia

Julia can be installed for your machine [here](https://julialang.org/downloads/).
For windows users, Julia can be installed from the Microsoft Store directly.
If you do not have admin permissions on your computer, installing Julia to your
local user is fine.

Check Julia is installed and recognised by typing `julia` in CMD or similar terminal.

### Open the repository in VSCode

If you do not have VSCode or Positron installed, these are useful IDEs for languages
such as Julia. 
The Julia language extension on these IDEs will provide highlighting
and file formatting.
The Quarto extension and application will allow for proper rendering of the
document and use of visual editing.

### Start Julia and the project environment

In VSCode you can open a new julia terminal using `Alt + J + O`.
Once you are in the julia terminal you can start the project environment manager
using `]`.
Once in the project environment manager use `activate .` to activate the project
environment. Once the project environment is activated (blue text in the folder name
will be displayed) use `instantiate` to install the correct packages that are
in the project repo (packages from `Project.toml`).

This is a standard procedure anytime you are activating a new project that has been
already set up by someone else (e.g. GitHub repository).

### Open and run through PMM_jl.qmd

This Quarto document contains the demonstration used in the presentation.
This document can be viewed in source mode or visual mode (if Quarto (and extension)
is installed). Use source mode to show canonical Julia syntax highlighting.