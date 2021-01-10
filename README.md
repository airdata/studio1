# The Basement Documentation
This is documentation is based on `Sphinx project` so you must install some prerequests to generate HTML files

[![CircleCI](https://img.shields.io/circleci/project/github/airdata/studio1.svg)](https://circleci.com/gh/airdata/studio1) 

## URL
[https://studio1.readthedocs.io/en/latest/](https://studio1.readthedocs.io/en/latest/)
## Prerequests
### Sphinx and rtd_theme
```
pip install sphinx sphinx_rtd_theme
```


## Generate this content to HTML
```
make html
```
### HTML Output
When you get `build succeeded.` from `make html` then you can find new directory named `build/html`. 

Inside you can find `.html` files.