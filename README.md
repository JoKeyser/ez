# ez

The aim of the `ez` package for R is to provide a simplified/unified interface to common analysis techniques, including analysis of variance and mixed effects modeling. 

This site not only hosts the ongoing code development for `ez`, but also serves as the forum (https://github.com/mike-lawrence/ez/issues) to report bugs and request features associated `ez`.

A discussion forum can be found at http://groups.google.com/group/ez4r

## Note:

To automatically download and install the very latest ez code any time you run a given R script, install the `devtools` library (`install.packages('devtools')`; windows users will also have to install Rtools, http://cran.r-project.org/bin/windows/Rtools/, and install devtools via `install.packages('devtools',type='source')`) then put the following at the top of your script:

    library(devtools)
    dev_mode()
    install_github('mike-lawrence/ez')
    library(ez)

