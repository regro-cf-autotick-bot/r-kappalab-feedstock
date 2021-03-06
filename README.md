About r-kappalab
================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

Home: https://CRAN.R-project.org/package=kappalab

Package license: CeCILL

Feedstock license: BSD 3-Clause

Summary: S4 tool box for capacity (or non-additive measure, fuzzy measure) and integral manipulation in a finite setting. It contains routines for handling various types of set functions such as games or capacities. It can be used to compute several non-additive integrals: the Choquet integral, the Sugeno integral, and the symmetric and asymmetric Choquet integrals. An analysis of capacities in terms of decision behavior can be performed through the computation of various indices such as the Shapley value, the interaction index, the orness degree, etc. The well-known Möbius transform, as well as other equivalent representations of set functions can also be computed. Kappalab further contains seven capacity identification routines: three least squares based approaches, a method based on linear programming, a maximum entropy like method based on variance minimization, a minimum distance approach and an unsupervised approach based on parametric entropies. The functions contained in Kappalab can for instance be used in the framework of multicriteria decision making or cooperative game theory.



Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/conda-forge/r-kappalab-feedstock/master.svg?label=Linux)](https://circleci.com/gh/conda-forge/r-kappalab-feedstock)
[![OSX](https://img.shields.io/travis/conda-forge/r-kappalab-feedstock/master.svg?label=macOS)](https://travis-ci.org/conda-forge/r-kappalab-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/conda-forge/r-kappalab-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/conda-forge/r-kappalab-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--kappalab-green.svg)](https://anaconda.org/conda-forge/r-kappalab) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-kappalab.svg)](https://anaconda.org/conda-forge/r-kappalab) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-kappalab.svg)](https://anaconda.org/conda-forge/r-kappalab) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-kappalab.svg)](https://anaconda.org/conda-forge/r-kappalab) |

Installing r-kappalab
=====================

Installing `r-kappalab` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `r-kappalab` can be installed with:

```
conda install r-kappalab
```

It is possible to list all of the versions of `r-kappalab` available on your platform with:

```
conda search r-kappalab --channel conda-forge
```


About conda-forge
=================

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-kappalab-feedstock
=============================

If you would like to improve the r-kappalab recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-kappalab-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@bgruening](https://github.com/bgruening/)
* [@cbrueffer](https://github.com/cbrueffer/)
* [@daler](https://github.com/daler/)
* [@dbast](https://github.com/dbast/)
* [@dpryan79](https://github.com/dpryan79/)
* [@jdblischak](https://github.com/jdblischak/)
* [@johanneskoester](https://github.com/johanneskoester/)

