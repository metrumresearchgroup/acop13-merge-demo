# acop13-merge-demo
MeRGE demonstration for ACoP 13 pre-conference workshop in Aurora, CO 30 October 2022.

Packages have been specified in _/renv_ and should be accessible by first running in your RStudio Console window:


~~~ 

install.packages("renv")
library(renv)
renv::restore()  

~~~

Users should respond "Yes" when asked to activate the project after calling `renv::restore()`

For further information on using renv, please see: https://rstudio.github.io/renv/articles/renv.html#reproducibility

Directory listing:

~~~
   /model = the NONMEM-formatted model files (.ctl)

   /script = the scripts that were demonstrated during the workshop
   
   /data = a simulated data file to use as example "observed" data
   
   /presentation = a pdf file with the hands-on slides for the workshop
