cxlb-docker-gnuradio-3.10
=========================

Docker image with a GNURadio-3.10 toolchain for CorteXlab.

quick howto
-----------

### Using the prebuilt image from GitHub Container Registry (recommended)

- pull and start the container:

    docker run -dti --net=host ghcr.io/cortexlab/cxlb-docker-gnuradio-3.10:latest

### Building locally

- build the docker image:

    docker build --network=host -t cxlb-gnuradio-3.10 .

- create and start a container:

    docker run -dti --net=host cxlb-gnuradio-3.10

### Connecting

- connect to this container with ssh:

    ssh -Xp 2222 root@localhost

