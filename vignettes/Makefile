all: compiled

compiled: 
	"${R_HOME}/bin/R" -e "final.dir <- '../inst/doc/book'; dir.create(final.dir, recursive=TRUE, showWarnings=FALSE); all.files <- list.files('../inst/book'); file.copy(file.path('../inst/book', all.files), file.path(final.dir, all.files));"
