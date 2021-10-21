# Fork of postgis/postgis

This is a fork of [postgis/postgis](https://github.com/postgis/docker-postgis/actions) in order to
rebuild the Debian container as a multiarch image for `linux/amd64` and `linux/arm64`. This
repository's GitHub Actions job to build a multiarch image will run [once per
week](https://github.com/baosystems/docker-postgis/blob/multiarch/.github/workflows/main.yml#L7),
one day after the [upstream has built new
images](https://github.com/postgis/docker-postgis/blob/master/.github/workflows/main.yml#L7).

No support is provided. If you do not understand the implications of using this image, do not use it
and instead of the [official PostGIS image](https://hub.docker.com/r/postgis/postgis).
