About fltk-feedstock
====================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/fltk-feedstock/blob/main/LICENSE.txt)

Home: https://www.fltk.org/

Package license: LGPL-2.0-or-later

Summary: The Fast Light Tool Kit ("FLTK", pronounced "fulltick") is a cross-platform C++ GUI toolkit

Development: https://github.com/fltk/fltk.git

Documentation: https://www.fltk.org/documentation.php

FLTK (pronounced "fulltick") is a cross-platform C++ GUI toolkit for
UNIX/Linux (X11), Microsoft Windows, and MacOS X. FLTK provides
modern GUI functionality without the bloat and supports 3D graphics via
OpenGL and its built-in GLUT emulation.

FLTK is designed to be small and modular enough to be statically
linked, but works fine as a shared library. FLTK also includes an
excellent UI builder called FLUID that can be used to create
applications in minutes.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5361&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/fltk-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5361&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/fltk-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5361&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/fltk-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5361&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/fltk-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=5361&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/fltk-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-fltk-green.svg)](https://anaconda.org/freecad/fltk) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/fltk.svg)](https://anaconda.org/freecad/fltk) | [![Conda Version](https://img.shields.io/conda/vn/freecad/fltk.svg)](https://anaconda.org/freecad/fltk) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/fltk.svg)](https://anaconda.org/freecad/fltk) |

Installing fltk
===============

Installing `fltk` from the `freecad` channel can be achieved by adding `freecad` to your channels with:

```
conda config --add channels freecad
conda config --set channel_priority strict
```

Once the `freecad` channel has been enabled, `fltk` can be installed with `conda`:

```
conda install fltk
```

or with `mamba`:

```
mamba install fltk
```

It is possible to list all of the versions of `fltk` available on your platform with `conda`:

```
conda search fltk --channel freecad
```

or with `mamba`:

```
mamba search fltk --channel freecad
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search fltk --channel freecad

# List packages depending on `fltk`:
mamba repoquery whoneeds fltk --channel freecad

# List dependencies of `fltk`:
mamba repoquery depends fltk --channel freecad
```




Updating fltk-feedstock
=======================

If you would like to improve the fltk recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/fltk-feedstock are
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

* [@guyer](https://github.com/guyer/)
* [@matthiasdiener](https://github.com/matthiasdiener/)

