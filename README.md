# Docker ML | Report Bee

The docker image comes with the following installed packages

  - tensorflow - 1.7
  - keras (latest)
  - numpy 1.13.3
  - scipy (latest)
  - sklearn (latest)
  - opencv-python (latest)
  - scikit-image (latest)
  - matplotlib (latest)
  - jupyter (latest)
  - Pillow (latest)

# How to run

  1. Install Docker engine (Checkout the official docs)
  2. Pull image - `docker pull kaushikrb/rb-ml`
  3. Run image - `docker run --rm -it -p 6006:6006 -p 8888:8888 kaushikrb/rb-ml`