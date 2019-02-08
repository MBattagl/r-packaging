# r-packaging

[![](https://images.microbadger.com/badges/image/methodsconsultants/r-packaging.svg)](https://microbadger.com/images/methodsconsultants/r-packaging)
[![](https://img.shields.io/docker/pulls/methodsconsultants/r-packaging.svg)](https://hub.docker.com/r/methodsconsultants/r-packaging)
[![](https://img.shields.io/docker/automated/methodsconsultants/r-packaging.svg)](https://hub.docker.com/r/methodsconsultants/r-packaging/builds)

A docker container for building R packages, intended for use in Continuous Integration systems like Gitlab or Circle.
From `rocker/r-base`, it adds the R packages `devtools` & `roxygen2`, as well as their system-level dependencies.
