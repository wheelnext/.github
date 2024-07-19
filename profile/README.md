# wheel-next

This repo is a place to build proof of concepts for python wheels in a public open space. The intention is to only add code that will be able to be merged with upstream projects, e.g. python, warehouse, scikit-build-core. Thus licenses and contributor license agreements will be goverened by the target project.

Current topics of interest:
* Additional metadata to capture different builds of otherwise-identical python packages (such as compiling with different shared library support)
  * https://discuss.python.org/t/what-to-do-about-gpus-and-the-built-distributions-that-support-them/7125
  * https://discuss.python.org/t/selecting-variant-wheels-according-to-a-semi-static-specification/53446
  * https://discuss.python.org/t/implementation-variants-rehashing-and-refocusing/54884
* Symlink support
  * https://discuss.python.org/t/pep-778-supporting-symlinks-in-wheels/53824
* Improving compression
  * https://discuss.python.org/t/making-the-wheel-format-more-flexible-for-better-compression-speed/3810
