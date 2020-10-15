# Setup Buildkite Plugin [![Version badge](https://img.shields.io/badge/setup-v0.1.10-blue?style=flat-square)](https://buildkite.com/plugins)


Similar to GitHub's `setup` actions like `setup-ruby` or `setup-node` but uses third party version managers to download binaries on various platforms. You must install;

- tj/n
- RVM
- Goenv

...to the EC2 Image or your on-premise servers to use this plugin. This plugin will simply read necessary version files and if they exists, it will install and use it.

### Not yet ready
This project is used inside of an organization, however, not quite ready for mass usage.

Copyright (C) 2020 Gencer W. Genç.

Licensed as **MIT**.
