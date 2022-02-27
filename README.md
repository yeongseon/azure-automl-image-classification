# azure-automl-image-classification

Usage
=====

* Build your own image and run it

 [Docker](https://www.docker.com) is a pre-requirement for this project. 
 You can build the container with:
 ```bash
  docker build -t azure-automl-jupyter-notebook . 
 ```
 The build process can take some time, but if finished you can run your container with:
 ```bash
  docker run -p 8888:8888 -i -t azure-automl-jupyter-notebook
 ```
 and you will have a running [Jupyter Notebook](http://jupyter.org) instance on ``http://localhost:8888/ipython/``.

