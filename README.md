# Raspberry Pi 1 NSD DNS Docker Image With Alpine Linux

[![Build Status](https://travis-ci.org/offtechnologies/docker-arm32v6-nsd.svg?branch=master)](travis-ci.org/offtechnologies/docker-arm32v6-nsd)
[![This image on DockerHub](https://img.shields.io/docker/pulls/offtechnologies/docker-arm32v6-nsd.svg)](https://hub.docker.com/r/offtechnologies/docker-arm32v6-nsd/)
[![](https://images.microbadger.com/badges/version/offtechnologies/docker-arm32v6-nsd.svg)](https://microbadger.com/images/offtechnologies/docker-arm32v6-nds "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/offtechnologies/docker-arm32v6-nsd.svg)](https://microbadger.com/images/offtechnologies/docker-arm32v6-nsd "Get your own image badge on microbadger.com")


[offtechurl]: https://offtechnologies.gthub.io

[![offtechnologies](https://raw.githubusercontent.com/offtechnologies/offtechnologies.github.io/master/logo.png)][offtechurl]

Raspberry Pi 1 compatible docker image with Alpine Linux and [NSD](https://www.nlnetlabs.nl/projects/nsd/) - an authoritative only, high performance, simple and open source name server. It is based on the
[hardware/nsd-dnssec](https://github.com/hardware/nsd-dnssec) image ported to the arm32v6 based Raspbery Pi 1.

## Credits/Usage

- [hardware/nsd-dnssec](https://github.com/hardware/nsd-dnssec)

## 1.0.0 - 2017-11-24
* First release
* Latest NSD version (4.1.17)
* Custom base image: Alpine Linux arm32v6 ver 3.6 with qemu-arm-static
* Tested on Raspberry Pi 1 Model B Rev 2 with Raspbian 4.9.51-1 and Docker v17.10.0-ce
