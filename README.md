# ![Tux](https://cdn2.iconfinder.com/data/icons/designer-skills/128/linux-server-system-platform-os-computer-penguin-64.png)apache-dcg

Generates Apache2 config files for custom domains.

[![Open Source Helpers](https://www.codetriage.com/throw-out-error/apache-dcg/badges/users.svg)](https://www.codetriage.com/throw-out-error/apache-dcg)

## Prerequisites

- Latest version of Python 3
- Apache2 installation

## Installation

- Run `pip3 install apache-dcg` to install this package.
- Run `sudo apache-dcg` to configure apache.

Running with sudo is only needed if you are reloading the config or copying the files to /etc/apache2\. I still recommend it in most cases.

## Development Build Instructions

- `git clone https://github.com/throw-out-error/apache-dcg.git`
- CD into the folder
- Run `./build.sh` to build the distribution files.
- Run `./run.sh` to run apache-dcg in development

## Credits

- Made by [@onyxcode](https://github.com/onyxcode) & [@creepinson](https://github.com/creepinson)
- Thanks to the [Python Help Community](https://discord.gg/python)
