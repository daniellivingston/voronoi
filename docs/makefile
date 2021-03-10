# Simple makefile for building VORONOI documentation.
# Run `make docs` to compile HTML documentation.

.PHONY: docs dev

docs : 
	hugo --minify --buildDrafts --theme kube --verbose

dev : 
	hugo server --watch --verbose