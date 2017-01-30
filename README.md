[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/blinky-tape-test-status.svg)](https://hub.docker.com/r/rubygem/blinky-tape-test-status/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/blinky-tape-test-status.svg)](https://hub.docker.com/r/rubygem/blinky-tape-test-status/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/blinky-tape-test-status.svg)](https://hub.docker.com/r/rubygem/blinky-tape-test-status/)
[![Gem Downloads](https://img.shields.io/gem/dt/blinky-tape-test-status.svg)](https://rubygems.org/gems/blinky-tape-test-status/)
# blinky-tape-test-status

Auto-Generated Docker image for blinky-tape-test-status to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/blinky-tape-test-status`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/blinky-tape-test-status`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/blinky-tape-test-status`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/blinky-tape-test-status/)
