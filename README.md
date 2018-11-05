# Anaconda Starter Kit

[![(https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

The purpose of this project is to provide unified software dependency support for the students.

Python 3 is used for the entirety of term 1.

There are two ways to get up and running:

## [Anaconda Environment](doc/configure_via_anaconda.md)

Get started [here](doc/configure_via_anaconda.md). More info [here](http://conda.pydata.org/docs/).

Supported Sytems: Linux (CPU), Mac (CPU), Windows (CPU)     

| Pros                         | Cons                                               |
|------------------------------|----------------------------------------------------|
| More straight-forward to use | AWS or GPU support is not built in (have to do this yourself)              |
| More community support       | Implementation is local and OS specific            |
| More heavily adopted         |                                                    |

## [Docker](doc/configure_via_docker.md)

Get started [here](doc/configure_via_docker.md). More info [here](http://docker.com).

Supported Systems : AWS (CPU, [GPU](doc/docker_for_aws.md)), Linux (CPU), Mac (CPU), Windows (CPU)     

| Pros                                | Cons                                 |
|-------------------------------------|--------------------------------------|
| Configure once for all environments | More challenging to use              |
| AWS, GPU support                    | Less community support               |
| Practice with Docker              | Have to manage images and containers |
|                                     |                                      |

## Trouble Shooting

If you get an Import Error on cv2 and have ROS installed. See [here](https://stackoverflow.com/questions/43019951/after-install-ros-kinetic-cannot-import-opencv#).
