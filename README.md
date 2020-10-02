# eic-spack-cvmfs-tests

This repository contains a test suite for the EIC Spack software stack on CernVM-FS.

The GitHub Actions Workflow in `.github/workflows/run-against-cvmfs.yml` will run all
files in `ci.d` (in order) every night at 1 AM.

Note: Files in `ci.d` must contain only upper- and lower-case letters, digits,
underscores or hyphens. Dots are not allowed.
