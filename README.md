About r-chromomap
=================

Home: https://CRAN.R-project.org/package=chromoMap

Package license: GPL-3.0-only

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-chromomap-feedstock/blob/main/LICENSE.txt)

Summary: Provides interactive, configurable and elegant graphics visualization of the chromosomes or chromosome regions of any living organism allowing users to map chromosome elements (like genes, SNPs etc.) on the chromosome plot. It introduces a special plot viz. the "chromosome heatmap" that, in addition to mapping elements, can visualize the data associated with chromosome elements (like gene expression) in the form of heat colors which can be highly advantageous in the scientific interpretations and research work. Because of the large size of the chromosomes, it is impractical to visualize each element on the same plot. However, the plot provides a magnified view for each of chromosome locus to render additional information and visualization specific for that location. You can map thousands of genes and can view all mappings easily. Users can investigate the detailed information about the mappings (like gene names or total genes mapped on a location) or can view the magnified single or double stranded view of the chromosome at a location showing each mapped element in sequential order. The package provide multiple features like visualizing multiple sets, chromosome heat-maps, group annotations, adding hyperlinks, and labelling. The plots can be saved as HTML documents that can be customized and shared easily. In addition, you can include them in R Markdown or in R 'Shiny' applications.

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=14514&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-chromomap-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--chromomap-green.svg)](https://anaconda.org/conda-forge/r-chromomap) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-chromomap.svg)](https://anaconda.org/conda-forge/r-chromomap) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-chromomap.svg)](https://anaconda.org/conda-forge/r-chromomap) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-chromomap.svg)](https://anaconda.org/conda-forge/r-chromomap) |

Installing r-chromomap
======================

Installing `r-chromomap` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-chromomap` can be installed with `conda`:

```
conda install r-chromomap
```

or with `mamba`:

```
mamba install r-chromomap
```

It is possible to list all of the versions of `r-chromomap` available on your platform with `conda`:

```
conda search r-chromomap --channel conda-forge
```

or with `mamba`:

```
mamba search r-chromomap --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-chromomap --channel conda-forge

# List packages depending on `r-chromomap`:
mamba repoquery whoneeds r-chromomap --channel conda-forge

# List dependencies of `r-chromomap`:
mamba repoquery depends r-chromomap --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [Anaconda-Cloud](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

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


Updating r-chromomap-feedstock
==============================

If you would like to improve the r-chromomap recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-chromomap-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/conda-forge/r/)

