# docker-jenkins-slave

[![Build Status](https://travis-ci.org/katosys/docker-jenkins-slave.svg?branch=master)](https://travis-ci.org/katosys/docker-jenkins-slave)

Containerized jenkins slave server.

```
docker run -it --rm \
--env SSL_TRUST=foo:443,bar:443 \
katosys/jenkins-slave \
/bin/bash
```
