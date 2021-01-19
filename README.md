## Week 2 Answers

`library(reticulate)` will load reticulate into R. Then `use_python("/path/to/python3.9")` to point to the desired version of python. In my case, I needed to use `Sys.setenv(RETICULATE_PYTHON = "/usr/local/bin/python3.9")` to get rid of some errors. 

What shell command do you use to find your Python path?

`which python3` and `which -a python python3.9` to get the link to the version 3.9 instead of 3.7, which seems to be my default.

What does include = FALSE do?

_does not include that chunk's contents in the html or pdf output file_

What happens if you remove the semicolon (‘;’) from the second to last line of the last code block?

_<seaborn.axisgrid.FacetGrid object at 0x155e80340> mapping object is shown; suppressed by the semicolon_
