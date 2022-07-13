# GrGadget

Welcome to GrGadget superproject!

This repository combines all the GrGadget dependencies that our team is maintaining, so that the end
user can get quickstarted into the project avoiding the nuances of installing and setting up an
environment for the individual components.

# Dependencies

- C++17 compiler
- MPI
- FFTW3 with parallel support
- boost
- hdf5 (with parallel support?)
- gls
- healpix (optional?)
- hwloc (optional?)

# Get started

```
git clone https://github.com/GrGadget/GrGadget-main.git
mkdir build && cd build
module load $dependencies
cp ../GrGadget-main/examples/Config.sh .
meson ../GrGadget-main
ninja
```
