# docker-sphinx
Sphinx documentation toolchain, latex dependencies and pandoc in an Ubuntu docker container.

## How to use it

`docker run -it -v <your directory>:/documents/ sogis/docker-sphinx`

Use sphinx-quickstart to create a new Sphinx project, and make to use the auto generated Makefile in an existing project. More info in the [Sphinx tutorial](http://www.sphinx-doc.org/en/stable/tutorial.html).
