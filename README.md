About libvips
=============

Home: https://libvips.github.io/libvips

Package license: LGPL-2.1

Feedstock license: [BSD-3-Clause](https://github.com/sdvillal/libvips-feedstock/blob/master/LICENSE.txt)

Summary: A fast image processing library with low memory needs

Development: https://github.com/libvips/libvips

Documentation: https://libvips.github.io/libvips/API/current

libvips is a demand-driven, horizontally threaded image processing
library. Compared to similar libraries, libvips runs quickly and uses
little memory.  It has around 300 operations covering arithmetic,
histograms, convolution, morphological operations, frequency filtering,
colour, resampling, statistics and others. It supports a large range of
numeric formats, from 8-bit int to 128-bit complex. Images can have any
number of bands. It supports a good range of image formats, including
JPEG, TIFF, OME-TIFF, PNG, WebP, FITS, Matlab, PDF, SVG, HDR,
PPM, CSV, GIF, Analyze, DeepZoom, and OpenSlide. It can also load images
via ImageMagick or GraphicsMagick, letting it load formats like DICOM.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/libvips-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/libvips-feedstock?branchName=master&jobName=linux&configuration=linux_64_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64</td>
              <td>
                <a href="https://dev.azure.com/sdvillal/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/sdvillal/feedstock-builds/_apis/build/status/libvips-feedstock?branchName=master&jobName=osx&configuration=osx_64_" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-libvips-green.svg)](https://anaconda.org/sdvillal/libvips) | [![Conda Downloads](https://img.shields.io/conda/dn/sdvillal/libvips.svg)](https://anaconda.org/sdvillal/libvips) | [![Conda Version](https://img.shields.io/conda/vn/sdvillal/libvips.svg)](https://anaconda.org/sdvillal/libvips) | [![Conda Platforms](https://img.shields.io/conda/pn/sdvillal/libvips.svg)](https://anaconda.org/sdvillal/libvips) |

Installing libvips
==================

Installing `libvips` from the `sdvillal` channel can be achieved by adding `sdvillal` to your channels with:

```
conda config --add channels sdvillal
```

Once the `sdvillal` channel has been enabled, `libvips` can be installed with:

```
conda install libvips
```

It is possible to list all of the versions of `libvips` available on your platform with:

```
conda search libvips --channel sdvillal
```




Updating libvips-feedstock
==========================

If you would like to improve the libvips recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sdvillal` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sdvillal` channel.
Note that all branches in the sdvillal/libvips-feedstock are
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

* [@jcupitt](https://github.com/jcupitt/)
* [@sdvillal](https://github.com/sdvillal/)
* [@sebastian-luna-valero](https://github.com/sebastian-luna-valero/)

