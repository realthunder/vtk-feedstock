About vtk-feedstock
===================

Feedstock license: [BSD-3-Clause](https://github.com/realthunder/vtk-feedstock/blob/main/LICENSE.txt)

Home: http://www.vtk.org/

Package license: BSD-3-Clause

Summary: The Visualization Toolkit (VTK) is an open-source, freely available software system for 3D computer graphics, modeling, image processing, volume rendering, scientific visualization, and information visualization.


Development: https://gitlab.kitware.com/vtk/vtk

Documentation: https://vtk.org/documentation

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-vtk-green.svg)](https://anaconda.org/realthunder/vtk) | [![Conda Downloads](https://img.shields.io/conda/dn/realthunder/vtk.svg)](https://anaconda.org/realthunder/vtk) | [![Conda Version](https://img.shields.io/conda/vn/realthunder/vtk.svg)](https://anaconda.org/realthunder/vtk) | [![Conda Platforms](https://img.shields.io/conda/pn/realthunder/vtk.svg)](https://anaconda.org/realthunder/vtk) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-vtk--base-green.svg)](https://anaconda.org/realthunder/vtk-base) | [![Conda Downloads](https://img.shields.io/conda/dn/realthunder/vtk-base.svg)](https://anaconda.org/realthunder/vtk-base) | [![Conda Version](https://img.shields.io/conda/vn/realthunder/vtk-base.svg)](https://anaconda.org/realthunder/vtk-base) | [![Conda Platforms](https://img.shields.io/conda/pn/realthunder/vtk-base.svg)](https://anaconda.org/realthunder/vtk-base) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-vtk--io--ffmpeg-green.svg)](https://anaconda.org/realthunder/vtk-io-ffmpeg) | [![Conda Downloads](https://img.shields.io/conda/dn/realthunder/vtk-io-ffmpeg.svg)](https://anaconda.org/realthunder/vtk-io-ffmpeg) | [![Conda Version](https://img.shields.io/conda/vn/realthunder/vtk-io-ffmpeg.svg)](https://anaconda.org/realthunder/vtk-io-ffmpeg) | [![Conda Platforms](https://img.shields.io/conda/pn/realthunder/vtk-io-ffmpeg.svg)](https://anaconda.org/realthunder/vtk-io-ffmpeg) |

Installing vtk
==============

Installing `vtk` from the `realthunder` channel can be achieved by adding `realthunder` to your channels with:

```
conda config --add channels realthunder
conda config --set channel_priority strict
```

Once the `realthunder` channel has been enabled, `vtk, vtk-base, vtk-io-ffmpeg` can be installed with `conda`:

```
conda install vtk vtk-base vtk-io-ffmpeg
```

or with `mamba`:

```
mamba install vtk vtk-base vtk-io-ffmpeg
```

It is possible to list all of the versions of `vtk` available on your platform with `conda`:

```
conda search vtk --channel realthunder
```

or with `mamba`:

```
mamba search vtk --channel realthunder
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search vtk --channel realthunder

# List packages depending on `vtk`:
mamba repoquery whoneeds vtk --channel realthunder

# List dependencies of `vtk`:
mamba repoquery depends vtk --channel realthunder
```




Updating vtk-feedstock
======================

If you would like to improve the vtk recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`realthunder` channel, whereupon the built conda packages will be available for
everybody to install and use from the `realthunder` channel.
Note that all branches in the realthunder/vtk-feedstock are
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

* [@Maxyme](https://github.com/Maxyme/)
* [@Tobias-Fischer](https://github.com/Tobias-Fischer/)
* [@basnijholt](https://github.com/basnijholt/)
* [@ccordoba12](https://github.com/ccordoba12/)
* [@dfroger](https://github.com/dfroger/)
* [@downiec](https://github.com/downiec/)
* [@grlee77](https://github.com/grlee77/)
* [@jasonb5](https://github.com/jasonb5/)
* [@marcelotrevisani](https://github.com/marcelotrevisani/)
* [@matthiasdiener](https://github.com/matthiasdiener/)
* [@msarahan](https://github.com/msarahan/)
* [@patricksnape](https://github.com/patricksnape/)
* [@tadeu](https://github.com/tadeu/)

