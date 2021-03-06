[![Follow on Twitter](https://img.shields.io/twitter/follow/pownjs.svg?logo=twitter)](https://twitter.com/pownjs)
[![NPM](https://img.shields.io/npm/v/@pown/webview.svg)](https://www.npmjs.com/package/@pown/webview)
[![Fury](https://img.shields.io/badge/version-2x%20Fury-red.svg)](https://github.com/pownjs/lobby)
[![SecApps](https://img.shields.io/badge/credits-SecApps-black.svg)](https://secapps.com)

# Pown Webview

Pown Webview is a helper tool and meta-library for running electron-based applications.

You can use it as a command-line tool but it is also meant to be used to import electron into other pown projects such that dependencies are maintained centrally.

## Credits

This tool is part of [secapps.com](https://secapps.com) open-source initiative.

```
  ___ ___ ___   _   ___ ___  ___
 / __| __/ __| /_\ | _ \ _ \/ __|
 \__ \ _| (__ / _ \|  _/  _/\__ \
 |___/___\___/_/ \_\_| |_|  |___/
  https://secapps.com
```

### Authors

* [@pdp](https://twitter.com/pdp) - https://pdparchitect.github.io/www/

## Quickstart

This tool is meant to be used as part of [Pown.js](https://github.com/pownjs/pown) but it can be invoked separately as an independent tool.

Install Pown first as usual:

```sh
$ npm install -g pown@latest
```

Invoke directly from Pown:

```sh
$ pown webview
```

### Library Use

Install this module locally from the root of your project:

```sh
$ npm install @pown/webview --save
```

Once done, invoke pown cli:

```sh
$ POWN_ROOT=. ./node_modules/.bin/pown-cli webview
```

You can also use the global pown to invoke the tool locally:

```sh
$ POWN_ROOT=. pown webview
```

## Usage

> **WARNING**: This pown command is currently under development and as a result will be subject to breaking changes.

```
pown webview <url>

Webview

Options:
  --version                    Show version number  [boolean]
  --help                       Show help  [boolean]
  --proxy-server               Use a specified proxy server, which overrides the system setting.  [string]
  --proxy-bypass-list            bypass the proxy server for the given semi-colon-separated list of hosts  [string]
  --no-proxy-server            Don't use a proxy server and always make direct connections.  [boolean]
  --ignore-certificate-errors  Ignore certificate errors.  [boolean]
```
