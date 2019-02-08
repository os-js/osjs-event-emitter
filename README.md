<p align="center">
  <img alt="OS.js Logo" src="https://raw.githubusercontent.com/os-js/gfx/master/logo-big.png" />
</p>

[OS.js](https://www.os-js.org/) is an [open-source](https://raw.githubusercontent.com/os-js/OS.js/master/LICENSE) desktop implementation for your browser with a fully-fledged window manager, Application APIs, GUI toolkits and filesystem abstraction.

[![Build Status](https://travis-ci.org/os-js/osjs-event-emitter.svg?branch=master)](https://travis-ci.org/os-js/osjs-event-emitter)
[![Maintainability](https://api.codeclimate.com/v1/badges/5a2f1be83828d59370bd/maintainability)](https://codeclimate.com/github/os-js/osjs-event-emitter/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/5a2f1be83828d59370bd/test_coverage)](https://codeclimate.com/github/os-js/osjs-event-emitter/test_coverage)
[![Community](https://img.shields.io/badge/join-community-green.svg)](https://community.os-js.org/)
[![Donate](https://img.shields.io/badge/liberapay-donate-yellowgreen.svg)](https://liberapay.com/os-js/)
[![Donate](https://img.shields.io/badge/paypal-donate-yellow.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=andersevenrud%40gmail%2ecom&lc=NO&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted)
[![Support](https://img.shields.io/badge/patreon-support-orange.svg)](https://www.patreon.com/user?u=2978551&ty=h&u=2978551)

# OS.js EventEmitter

This is a EventEmitter implementation for OS.js.

## API

```
on('event-name', () => {}); // Fired every time event is emitted
once('event-name', () => {}); // Fires only once and is forgotten
off('event-name', () => {}); // Removes listener
off('event-name'); // Removes all listeners of this type
off(); // Removes all listeners

on('event-name', () => {}, {persist: true}); // Will not be removed unless forced
off('event-name', () => {}, true); // Force removal
```

## Contribution

* **Become a [Patreon](https://www.patreon.com/user?u=2978551&ty=h&u=2978551)**
* **Support on [Open Collective](https://opencollective.com/osjs)**
* [Contribution Guide](https://github.com/os-js/OS.js/blob/v3/CONTRIBUTING.md)

## Documentation

See the [Official Manuals](https://manual.os-js.org/v3/) for articles, tutorials and guides.

## Links

* [Official Chat](https://gitter.im/os-js/OS.js)
* [Community Forums and Announcements](https://community.os-js.org/)
* [Homepage](https://os-js.org/)
* [Twitter](https://twitter.com/osjsorg) ([author](https://twitter.com/andersevenrud))
* [Google+](https://plus.google.com/b/113399210633478618934/113399210633478618934)
* [Facebook](https://www.facebook.com/os.js.org)
* [Docker Hub](https://hub.docker.com/u/osjs/)
