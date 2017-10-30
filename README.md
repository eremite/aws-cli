# eremite/aws-cli

An alpine based [docker image](https://hub.docker.com/r/eremite/aws-cli/) with AWS tools including:

* aws
* eb
* s3cmd
* git (for `eb init`)
* ssh (for `eb ssh`)
* python-magic (for `s3cmd`)
* jq (for parsing json responses)

## Versioning

Starting at 1.1.1, any change to the following will trigger the corresponding major, minor and patch
versions to be incremented.

Current version: 1.3.2

* [alpine](https://hub.docker.com/r/library/alpine/tags/) 3.6
* [aws-cli](https://github.com/aws/aws-cli/releases) 1.11.178
* [s3cmd](https://github.com/s3tools/s3cmd/releases) 2.0.1
* [awsebcli](https://pypi.python.org/pypi/awsebcli/) 3.12.0
