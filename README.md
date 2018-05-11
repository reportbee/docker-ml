# Docker ML | Report Bee

![Docker Stars](https://img.shields.io/docker/stars/reportbee/datascience.svg?style=flat-square)  ![Docker Pulls](https://img.shields.io/docker/pulls/reportbee/datascience.svg?style=flat-square)  

The docker image comes with the following installed packages

  - Base OS: (Ubuntu 18.04)
  - Python Version: 3.6
  - Tensorflow - 1.7
  - Keras (latest)
  - Numpy 1.13.3
  - Scipy (latest)
  - Sklearn (latest)
  - Open CV (latest)
  - Scikit Image (latest)
  - Matplotlib (latest)
  - Jupyter Notebook (latest)
  - Pillow (latest)

# How to run

  1. Install Docker CE ([Install])
  2. Pull image - `docker pull reportbee/datascience`
  3. Run image - `docker run --restart unless-stopped -p 6006:6006 -p 8888:8888 reportbee/datascience`

# Quick References

  - **Where to raise issues ?**
  [Github Issues]
  - **Maintained by**
  [Report Bee]
  - **Image Source**
  [Github]
   
[Install]: <https://www.docker.com/community-edition>
[Github]: <https://github.com/reportbee/docker-ml>
[Github Issues]: <https://github.com/reportbee/docker-ml/issues>
[Report Bee]: <https://www.reportbee.com>