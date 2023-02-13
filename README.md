About m2w64-htslib
==================

Home: https://github.com/samtools/htslib

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/jdblischak/m2w64-htslib-feedstock/blob/main/LICENSE.txt)

Summary: C library for high-throughput sequencing data formats.

Development: https://github.com/TileDB-Inc/m2w64-htslib-build

Documentation: http://www.htslib.org/

The conda binary m2w64-htslib bundles a pre-built htslib binary that was
built under msys2. All dependencies are statically linked, with the
exception of .DLLs provided by Windows. It is suitable for linking against
in conda recipes that build using MSVC


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/jdblischak/feedstock-builds/_build/latest?definitionId=5&branchName=main">
            <img src="https://dev.azure.com/jdblischak/feedstock-builds/_apis/build/status/m2w64-htslib-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>win_64</td>
              <td>
                <a href="https://dev.azure.com/jdblischak/feedstock-builds/_build/latest?definitionId=5&branchName=main">
                  <img src="https://dev.azure.com/jdblischak/feedstock-builds/_apis/build/status/m2w64-htslib-feedstock?branchName=main&jobName=win&configuration=win%20win_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-m2w64--htslib-green.svg)](https://anaconda.org/jdblischak/m2w64-htslib) | [![Conda Downloads](https://img.shields.io/conda/dn/jdblischak/m2w64-htslib.svg)](https://anaconda.org/jdblischak/m2w64-htslib) | [![Conda Version](https://img.shields.io/conda/vn/jdblischak/m2w64-htslib.svg)](https://anaconda.org/jdblischak/m2w64-htslib) | [![Conda Platforms](https://img.shields.io/conda/pn/jdblischak/m2w64-htslib.svg)](https://anaconda.org/jdblischak/m2w64-htslib) |

Installing m2w64-htslib
=======================

Installing `m2w64-htslib` from the `jdblischak` channel can be achieved by adding `jdblischak` to your channels with:

```
conda config --add channels jdblischak
conda config --set channel_priority strict
```

Once the `jdblischak` channel has been enabled, `m2w64-htslib` can be installed with `conda`:

```
conda install m2w64-htslib
```

or with `mamba`:

```
mamba install m2w64-htslib
```

It is possible to list all of the versions of `m2w64-htslib` available on your platform with `conda`:

```
conda search m2w64-htslib --channel jdblischak
```

or with `mamba`:

```
mamba search m2w64-htslib --channel jdblischak
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search m2w64-htslib --channel jdblischak

# List packages depending on `m2w64-htslib`:
mamba repoquery whoneeds m2w64-htslib --channel jdblischak

# List dependencies of `m2w64-htslib`:
mamba repoquery depends m2w64-htslib --channel jdblischak
```




Updating m2w64-htslib-feedstock
===============================

If you would like to improve the m2w64-htslib recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`jdblischak` channel, whereupon the built conda packages will be available for
everybody to install and use from the `jdblischak` channel.
Note that all branches in the jdblischak/m2w64-htslib-feedstock are
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

* [@dhoke4tdb](https://github.com/dhoke4tdb/)
* [@ihnorton](https://github.com/ihnorton/)
* [@jdblischak](https://github.com/jdblischak/)
* [@shelnutt2](https://github.com/shelnutt2/)

