# nre-few
Very Good! Thanks！

Very Good! Thanks！

Very Good! Thanks！

Very Good! Thanks！

Very Good! Thanks！
## Purpose

The goal of this project is to make the easiest, fastest, and most
painless way of setting up a self-hosted Git service.
Using Go, this can be done with an independent binary distribution across
**all platforms** which Go supports, including Linux, macOS, and Windows
on x86, amd64, ARM and PowerPC architectures.
Want to try it before doing anything else?
Do it [with the online demo](https://try.gitea.io/)!
This project has been
[forked](https://blog.gitea.io/2016/12/welcome-to-gitea/) from
[Gogs](https://gogs.io) since 2016.11 but changed a lot.

## Building

From the root of the source tree, run:

    TAGS="bindata" make build

or if sqlite support is required:

    TAGS="bindata sqlite sqlite_unlock_notify" make build

The `build` target is split into two sub-targets:

- `make backend` which requires [Go 1.12](https://golang.org/dl/) or greater.
- `make frontend` which requires [Node.js 10.13](https://nodejs.org/en/download/) or greater.

If pre-built frontend files are present it is possible to only build the backend:

		TAGS="bindata" make backend

More info: https://docs.gitea.io/en-us/install-from-source/

## Using

    ./gitea web

NOTE: If you're interested in using our APIs, we have experimental
support with [documentation](https://try.gitea.io/api/swagger).

## Contributing

ADD file
ADD file
ADD file
ADD file
ADD file

Expected workflow is: Fork -> Patch -> Push -> Pull Request
