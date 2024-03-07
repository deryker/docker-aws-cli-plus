# docker-aws-cli

[![CircleCI](https://dl.circleci.com/status-badge/img/circleci/TCMXHRSwooS96tKrJmNct2/XU5TkUcZTS9pLnh42u4w2E/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/circleci/TCMXHRSwooS96tKrJmNct2/XU5TkUcZTS9pLnh42u4w2E/tree/master)

## Description

Docker with aws cli and kubectl for CI/CD purpose

This image is based on debian buster slim and contains:

- Python 3.9
- Pip3 20.3
- Aws cli 1.27
- s3cmd 2.3
- Kubectl 1.25
- Curl
- Git
- Docker cli 20.10
- Jq 1.6
- YTT v0.45.3 (Yaml templating tool https://github.com/vmware-tanzu/carvel-ytt)
- Helm 3

This image is intended to be used in an AWS and Kubernetes CI/CD environment.

## Flavors

This build provides two flavors:

- deryker/aws-cli-plus:VERSION

Which include all tools from the `description`

- deryker/aws-cli-plus:VERSION-serverless

Which contains all tools from the `description` and serverless.com cli

## DockerHub

Available publicly on:

- https://hub.docker.com/r/deryker/docker-aws-cli-plus

## Reference

Thanks to Jérémy Marjollet.

- https://github.com/aegirops/docker-aws-cli
- https://hub.docker.com/r/aegirops/aws-cli
