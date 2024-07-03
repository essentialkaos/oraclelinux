<p align="center"><a href="#readme"><img src=".github/images/card.svg"/></a></p>

<p align="center">
  <a href="https://kaos.sh/w/oraclelinux/cd"><img src="https://kaos.sh/w/oraclelinux/cd.svg" alt="GitHub Actions CD Status" /></a>
  <a href="#license"><img src=".github/images/license.svg"/></a>
</p>

<p align="center"><a href="#usage">Usage</a> • <a href="#contributing">Contributing</a> • <a href="#license">License</a></p>

<br/>

This repository contains Dockerfiles for Oracle Linux 8, and 9 for automatic image rebuild with the latest packages installed. The resulting images are usually bigger than base images but more secure (_due to the very long period between base images rebuild_).

> [!IMPORTANT]
> **This project is not affiliated with Oracle Corporation and not officially supported by Oracle Corporation.**

### Usage

Using DockerHub:

```bash
docker pull essentialkaos/oraclelinux:8
docker pull essentialkaos/oraclelinux:8-slim
docker pull essentialkaos/oraclelinux:9
docker pull essentialkaos/oraclelinux:9-slim
```

Using GitHub Container Registry:

```bash
docker pull ghcr.io/essentialkaos/oraclelinux:8
docker pull ghcr.io/essentialkaos/oraclelinux:8-slim
docker pull ghcr.io/essentialkaos/oraclelinux:9
docker pull ghcr.io/essentialkaos/oraclelinux:9-slim
```

### Contributing

Before contributing to this project please read our [Contributing Guidelines](https://github.com/essentialkaos/contributing-guidelines#contributing-guidelines).

### License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
