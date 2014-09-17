# Repository of Linux Kernel suitability tests for Garden containers

`garden-linux-kernel-acceptance` is a respository designed to hold simple executable tests
to run in a linux system to determine if the kernel is configured correctly to allow Garden
containers to be constructed and used.

The aim is to build a suite of tests which can validate a particular kernel prior to using
it in container deployments.

Vagrantfiles for the various kernels are provided in the `vagrant` subdirectory.

You must set `$GOHOME` before bringing up any of the Vagrant machines in this repository. It is normal to set `$GOHOME` to the first element of `$GOPATH`.