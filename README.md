# Memcached

Small image (~3 MB) for Memcached based on Alpine Linux.

## Environment variables

### MEMCACHED_MEMORY_LIMIT

Memory limit for ``memcached`` in MB.

Default: 64

## Setup

### Docker

    docker run --detach --publish 11211:11211 foobox/memcached:1.5
