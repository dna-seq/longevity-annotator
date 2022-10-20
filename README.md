# longevity-annotator
Annotator for genetic polymorphism associated with longevity.

It was originally based on [Longevity Map Database](https://genomics.senescence.info/longevity/) that was severely extended by the team.
It contains research and publications related to longevity and ranges them by significance. 

Longevity annotator aggregates all research by rsid to feet annotator output format. 
It depends on DBSNP module and is a main source for longevity reporter.

# Installing the annotator in OakVar

Stable version of longevity annotator is published at oakvar store while master branch is based on development version and is used in development version of oakvar.
On a system with OakVar installed you can install longevity annotator with:
```
ov module install longevitymap
```
or directly from the github with:
```
ov module install https://github.com/dna-seq/longevity-annotator
```
We provide environment.yaml in case if you want to set up a clean environment with oakvar for longevity annotator development with micromamba or conda.

# Setting up github repository

The recommended way of development is using [oakvar-longevity](https://github.com/dna-seq/oakvar-longevity) repository that has all our major annotators and reporters imported as git submodules.
However, if it is more convenient for you to directly edit this repository, you can clone it by:
Fit clone the repository.
```
git clone git@github.com:dna-seq/longevity-annotator.git
```
than you can use micromamba, conda or anaconda to install the environment with:
```bash
micromamba create --file environment.yaml
micromamba activate oakvar-longevity
```

# Documentation

Please, refer to [Just-DNA-Seq readthedocs](https://just-dna-seq.readthedocs.io/en/oakvar/viewing-reports.html#part-1-longevity-significant-variations) for Documentation.