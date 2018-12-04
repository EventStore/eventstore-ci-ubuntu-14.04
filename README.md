# Description
Docker Image for build of EventStore on Ubuntu 14.04 (trusty) hosted at https://hub.docker.com/r/eventstore/eventstore-ci-ubuntu-14.04/
The build is currently used by our CI (Azure Pipelines)

### Base Image: `ubuntu:14.04`  
### Installs:
- mono 5.16.0
- dotnet-sdk-2.1
- node.js 8.11.4
- fpm (latest)
- awscli (latest)