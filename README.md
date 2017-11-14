## Packrat test

Provided that the packrat.lock file is distributed with the Rmd, the Rmd should be able to install Packrat, initialise Packrat in the directory, restart the R session, *copy the packrat.lock snapshot file to the newly-created packrat subdirectory*, and finally restore the library state from the snapshot. Doesn't seem to work with github install.
