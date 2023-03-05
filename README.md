About ilpy-feedstock
====================

Feedstock license: [BSD-3-Clause](https://github.com/tlambert03/ilpy-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/funkelab/ilpy

Package license: MIT

Summary: Unified python wrappers for popular ILP solvers

Current build status
====================


<table><tr>
    <td>CircleCI</td>
    <td>
      <a href="https://circleci.com/gh/tlambert03/ilpy-feedstock">
        <img alt="Linux,OSX,osx_arm64" src="https://img.shields.io/circleci/project/github/tlambert03/ilpy-feedstock/main.svg?label=Linux,OSX,osx_arm64">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-ilpy-green.svg)](https://anaconda.org/funkelab/ilpy) | [![Conda Downloads](https://img.shields.io/conda/dn/funkelab/ilpy.svg)](https://anaconda.org/funkelab/ilpy) | [![Conda Version](https://img.shields.io/conda/vn/funkelab/ilpy.svg)](https://anaconda.org/funkelab/ilpy) | [![Conda Platforms](https://img.shields.io/conda/pn/funkelab/ilpy.svg)](https://anaconda.org/funkelab/ilpy) |

Installing ilpy
===============

Installing `ilpy` from the `funkelab` channel can be achieved by adding `funkelab` to your channels with:

```
conda config --add channels funkelab
conda config --set channel_priority strict
```

Once the `funkelab` channel has been enabled, `ilpy` can be installed with `conda`:

```
conda install ilpy
```

or with `mamba`:

```
mamba install ilpy
```

It is possible to list all of the versions of `ilpy` available on your platform with `conda`:

```
conda search ilpy --channel funkelab
```

or with `mamba`:

```
mamba search ilpy --channel funkelab
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search ilpy --channel funkelab

# List packages depending on `ilpy`:
mamba repoquery whoneeds ilpy --channel funkelab

# List dependencies of `ilpy`:
mamba repoquery depends ilpy --channel funkelab
```




Updating ilpy-feedstock
=======================

If you would like to improve the ilpy recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`funkelab` channel, whereupon the built conda packages will be available for
everybody to install and use from the `funkelab` channel.
Note that all branches in the tlambert03/ilpy-feedstock are
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

* [@funkey](https://github.com/funkey/)
* [@tlambert03](https://github.com/tlambert03/)

