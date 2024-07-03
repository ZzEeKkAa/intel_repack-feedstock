About intel_repack-feedstock
============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/intel_repack-feedstock/blob/main/LICENSE.txt)


About intel_repack
------------------

Home: https://github.com/conda-forge/intel_repack-feedstock

Package license: LicenseRef-IntelSimplifiedSoftwareOct2022

Summary: Repackaged Intel libraries

About mkl
---------

Home: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html

Package license: LicenseRef-IntelSimplifiedSoftwareOct2022

Summary: Intel® oneAPI Math Kernel Library runtime libraries

Documentation: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html

Intel® oneAPI Math Kernel Library is Intel®-Optimized Math Library for Numerical Computing on CPUs & GPUs
This package is a repackaged set of binaries obtained directly from Intel\'s anaconda.org channel.


About mkl-include
-----------------

Home: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html

Package license: LicenseRef-IntelSimplifiedSoftwareOct2022

Summary: Headers for building against Intel® oneMKL libraries

Documentation: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html

Intel® oneAPI Math Kernel Library headers for developing software that uses oneMKL
This package is a repackaged set of binaries obtained directly from Intel\'s anaconda.org channel.


About mkl-devel
---------------

Home: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html

Package license: LicenseRef-IntelSimplifiedSoftwareOct2022

Summary: Devel package for building against Intel® oneMKL libraries

Intel® oneAPI Math Kernel Library headers and libraries for developing software that uses oneMKL
This package is a repackaged set of binaries obtained directly from Intel\'s anaconda.org channel.


About mkl-static
----------------

Home: https://www.intel.com/content/www/us/en/developer/tools/oneapi/onemkl.html

Package license: LicenseRef-IntelSimplifiedSoftwareOct2022

Summary: Static libraries for Intel® oneMKL libraries

Intel® oneAPI Math Kernel Library static libraries for developing software that uses oneMKL
This package is a repackaged set of binaries obtained directly from Intel\'s anaconda.org channel.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=8901&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/intel_repack-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=8901&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/intel_repack-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=8901&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/intel_repack-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mkl-green.svg)](https://anaconda.org/conda-forge/mkl) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mkl.svg)](https://anaconda.org/conda-forge/mkl) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mkl.svg)](https://anaconda.org/conda-forge/mkl) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mkl.svg)](https://anaconda.org/conda-forge/mkl) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mkl--devel-green.svg)](https://anaconda.org/conda-forge/mkl-devel) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mkl-devel.svg)](https://anaconda.org/conda-forge/mkl-devel) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mkl-devel.svg)](https://anaconda.org/conda-forge/mkl-devel) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mkl-devel.svg)](https://anaconda.org/conda-forge/mkl-devel) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mkl--include-green.svg)](https://anaconda.org/conda-forge/mkl-include) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mkl-include.svg)](https://anaconda.org/conda-forge/mkl-include) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mkl-include.svg)](https://anaconda.org/conda-forge/mkl-include) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mkl-include.svg)](https://anaconda.org/conda-forge/mkl-include) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mkl--static-green.svg)](https://anaconda.org/conda-forge/mkl-static) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/mkl-static.svg)](https://anaconda.org/conda-forge/mkl-static) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/mkl-static.svg)](https://anaconda.org/conda-forge/mkl-static) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/mkl-static.svg)](https://anaconda.org/conda-forge/mkl-static) |

Installing intel_repack
=======================

Installing `intel_repack` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `mkl, mkl-devel, mkl-include, mkl-static` can be installed with `conda`:

```
conda install mkl mkl-devel mkl-include mkl-static
```

or with `mamba`:

```
mamba install mkl mkl-devel mkl-include mkl-static
```

It is possible to list all of the versions of `mkl` available on your platform with `conda`:

```
conda search mkl --channel conda-forge
```

or with `mamba`:

```
mamba search mkl --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search mkl --channel conda-forge

# List packages depending on `mkl`:
mamba repoquery whoneeds mkl --channel conda-forge

# List dependencies of `mkl`:
mamba repoquery depends mkl --channel conda-forge
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
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
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


Updating intel_repack-feedstock
===============================

If you would like to improve the intel_repack recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/intel_repack-feedstock are
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

* [@ZzEeKkAa](https://github.com/ZzEeKkAa/)
* [@alexsandruss](https://github.com/alexsandruss/)
* [@beckermr](https://github.com/beckermr/)
* [@isuruf](https://github.com/isuruf/)
* [@napetrov](https://github.com/napetrov/)
* [@oleksandr-pavlyk](https://github.com/oleksandr-pavlyk/)

