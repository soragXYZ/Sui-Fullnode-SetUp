# Sui Fullnode Installation Guide

## Official Documentation
https://docs.sui.io/build/fullnode

## Prerequisites

### Packages
```
apt-get update \
&& apt-get install -y --no-install-recommends \
tzdata \
ca-certificates \
build-essential \
pkg-config \
cmake
```

### Docker

https://docs.docker.com/
```
apt-get install -y \
docker.io
```

## Sui Installation

### Fullnode template
```
wget https://github.com/MystenLabs/sui/raw/main/crates/sui-config/data/fullnode-template.yaml
```

