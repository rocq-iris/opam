# OPAM repository for Iris and related projects

This OPAM repository provides development versions of Iris and related projects.
The versions here are automatically created when things are pushed to the
respective repositories.  The updater and all documentation lives at
<https://gitlab.mpi-sws.org/iris/opam-updater> (this is a private project).

This repository does not contain all versions that were ever published; old
versions have been moved to <https://gitlab.mpi-sws.org/iris/opam-old>. If you
are trying to build an old Iris-based development and it is missing a package,
try adding the repo with the archived versions:

    opam repo add iris-dev-old https://gitlab.mpi-sws.org/iris/opam-old.git

Note that this can make opam very slow because of the sheer number of versions
that packages like `coq-iris` have in this repository.
