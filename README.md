# azure-automl-image-classification

Usage
=====

* Build your own image and run it

 [Docker](https://www.docker.com) is a pre-requirement for this project. You can build the container with:
 ```bash
  docker build -t jupyter-notebook . 
 ```
 The build process can take some time, but if finished you can run your container with:
 ```bash
  docker run -p 7777:8888 -i -t jupyter-notebook
 ```
 and you will have a running [Jupyter Notebook](http://jupyter.org) instance on ``http://localhost:7777/ipython/``.

* Run a pre-build image from docker registry

 ``docker run -p 7777:8888 bgruening/docker-jupyter-notebook ``  
