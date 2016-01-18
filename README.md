## Listing of mart instances

Since the BioMart community portal has been
[unavailable](http://www.biomart.org/notice.html) for quite some time,
it becomes more difficult to query
[non-mainstream](https://support.bioconductor.org/p/75730/#75786) mart
instances (essentially all other than ENSEMBL marts). 


The [`marts`](https://github.com/lgatto/marts/blob/master/marts.md)
vignette tries to access these community mart instances and acts as a
reference to manually set `host` and `path` when using
[`biomaRt`](http://bioconductor.org/packages/devel/bioc/html/biomaRt.html). These
variables are non-functional for several of these instances. If you
can correct them, please either send a pull request or [open an
issue](https://github.com/lgatto/marts/issues).