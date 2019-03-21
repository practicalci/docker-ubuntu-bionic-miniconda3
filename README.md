[![Docker Stars](https://img.shields.io/docker/stars/practicalci/ubuntu-bionic-miniconda3.svg?style=flat-square)](https://hub.docker.com/r/practicalci/ubuntu-bionic-miniconda3/)
[![Docker Pulls](https://img.shields.io/docker/pulls/practicalci/ubuntu-bionic-miniconda3.svg?style=flat-square)](https://hub.docker.com/r/practicalci/ubuntu-bionic-miniconda3/)

Base image to support miniconda environments, mapping the current working directory. Docker image
==========================================

This docker image used as a base for building developmenThis docker image used as a base for building development and build environments for C++, python possibly other languages, using conda depedency management tool.

Download size of this image is only:
[![](https://images.microbadger.com/badges/image/practicalci/ubuntu-bionic-miniconda3.svg)](http://microbadger.com/images/practicalci/ubuntu-bionic-miniconda3 "Get your own image badge on microbadger.com")


Usage Example
-------------

This image is intended to be a base image for your projects, so you may use it like this:

```
Dockerfile
    FROM practicalci/ubuntu-bionic-miniconda3

    COPY ./my_app /usr/local/bin/my_app
```

```
sh
  $ docker build -t my_app .
```

Build image in Docker Hub 
-------------------------

This template assumes you to be registered in Docker Hub.
To setup automated build via Docker Hub refer to: [Set up Automated builds](https://docs.docker.com/docker-hub/builds/).

To configure automated builds follow this link [Build configurations](https://cloud.docker.com/u/practicalci/repository/docker/practicalci/ubuntu-bionic-miniconda3/builds/edit)


Release a new image
-------------------

Make your changes and bump the image version with one of the commands, depending on the version bump:

```
sh
  $ bump2version part major
  $ bump2version part minor
  $ bump2version part patch
```

License
-------

This project is licensed under: [BSD-3-Clause](https://tldrlegal.com/license/bsd-3-clause-license-(revised))


Attributions
------------

Add below authors and licenses from which your work derives from, if any.

This work is derived from the work of:

| Author            | Work Source                                  | License                      |
|:------------------|:---------------------------------------------|:-----------------------------|
| Add Some Author   | <https://some-author-work-source-url>        | [some-author-license.txt](./attributions/some-author-license.txt) |

References
----------

List of references
