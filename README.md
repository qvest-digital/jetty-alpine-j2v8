# openjdk-alpine-j2v8

Jetty-alpine-j2v8 is an extension to the [jetty](https://github.com/appropriate/docker-jetty) Alpine flavored Docker image, allowing to run [J2V8](https://github.com/eclipsesource/J2V8) Java applications on Alpine systems. This is achieved by recompiling the J2V8 bindings with musl in Alpine.

This image comes in an JRE variant only, since jetty only provides JRE images.

## Why?

For more details on why this image exists, look at the README of the [openjdk-alpine-j2v8](https://github.com/tarent/openjdk-alpine-j2v8) project.