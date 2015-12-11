# docker-jenkins-slave

[![Build Status](https://travis-ci.org/h0tbird/docker-jenkins-slave.svg?branch=master)](https://travis-ci.org/h0tbird/docker-jenkins-slave)

Containerized jenkins slave server.

```
docker run -it --rm \
--env SSL_TRUST=foo:443,bar:443 \
h0tbird/jenkins-slave \
/bin/bash
```
