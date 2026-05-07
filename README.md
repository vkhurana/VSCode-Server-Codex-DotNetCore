# VSCode Server with .NET Pre-Installed

This is a docker image of VSCode Server with the .NET LTS and STS SDK's pre-installed.  
Docker image is based on [LinuxServer.io Code-Server](https://github.com/linuxserver/docker-code-server), which is based on [Coder.com Code-Server](https://github.com/cdr/code-server).  

## License

![GitHub License](https://img.shields.io/github/license/vkhurana/VSCode-Server-Codex-DotNetCore)  

## Build Status

[Code and Pipeline is on GitHub](https://github.com/vkhurana/VSCode-Server-Codex-DotNetCore):  
![GitHub Last Commit](https://img.shields.io/github/last-commit/vkhurana/VSCode-Server-Codex-DotNetCore?logo=github)  
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/vkhurana/VSCode-Server-Codex-DotNetCore/BuildPublishPipeline.yml?logo=github)

## Container Images

Docker container images are published on [Docker Hub](https://hub.docker.com/r/vkhurana/VSCode-Server-Codex-DotNetCore).  
Multi-Architecture images are created for `linux/amd64` and `linux/arm64` (`linux/arm/v7` is [not supported](https://www.linuxserver.io/blog/a-farewell-to-arm-hf) by LSIO).  
Tags are `latest` for `main` branch and `develop` for `develop` branch.  
E.g. `docker pull vkhurana/VSCode-Server-Codex-DotNetCore:latest`  
E.g. `docker pull vkhurana/VSCode-Server-Codex-DotNetCore:develop`

Builds include the LTS and STS [supported versions](https://dotnet.microsoft.com/en-us/platform/support/policy/dotnet-core) of .NET SDK's.

Images are automatically rebuilt every Monday morning, picking up the latest upstream updates.  
![Docker Pulls](https://img.shields.io/docker/pulls/vkhurana/VSCode-Server-Codex-DotNetCore?logo=docker)  
![Docker Image Version](https://img.shields.io/docker/v/vkhurana/VSCode-Server-Codex-DotNetCore/latest?logo=docker)

## Usage

Follow the [linuxserver/code-server](https://github.com/linuxserver/docker-code-server) instructions.
