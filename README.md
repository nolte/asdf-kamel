# asdf-kamel
Plugin for [asdf](https://github.com/asdf-vm/asdf) Package Manager, install [camel-k](https://github.com/apache/camel-k/) cli.

## Install

Look for the Latest Release of [go-task/task](https://github.com/go-task/task/releases).

```sh
asdf plugin-add task https://github.com/nolte/asdf-kamel.git

asdf install kamel 1.7.0
```

For the latest release take a look to the [Github releases](https://github.com/apache/camel-k/releases).

## Development


Direct call, for local development.
```sh
ASDF_INSTALL_TYPE=test \
  ASDF_INSTALL_VERSION=1.7.0 \
  ASDF_INSTALL_PATH=/tmp/plugin \
  ./bin/install
```
