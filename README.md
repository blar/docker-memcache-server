# Memcached

![Docker Pulls](https://img.shields.io/docker/pulls/foobox/memcache-server.svg)
![Docker Stars](https://img.shields.io/docker/stars/foobox/memcache-server.svg)

[![](https://images.microbadger.com/badges/version/foobox/memcache-server:1.10-amd64.svg)](https://microbadger.com/images/foobox/docker-beanstalk-server:1.10-amd64 "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/foobox/memcache-server:1.10-amd64.svg)](https://microbadger.com/images/foobox/docker-beanstalk-server:1.10-amd64 "Get your own image badge on microbadger.com")

[![](https://images.microbadger.com/badges/version/foobox/memcache-server:1.10-arm32v6.svg)](https://microbadger.com/images/foobox/docker-beanstalk-server:1.10-arm32v6 "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/foobox/memcache-server:1.10-arm32v6.svg)](https://microbadger.com/images/foobox/docker-beanstalk-server:1.10-arm32v6 "Get your own image badge on microbadger.com")

Small image (~3 MB) for Memcached based on Alpine Linux.

## Environment variables

### MEMCACHED_MEMORY_LIMIT

Memory limit for ``memcached`` in MB.

Default: 64

## Setup

### Docker

    docker run --detach --publish 11211:11211 foobox/memcached:1.5
