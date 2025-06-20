# EDGE - egguy addons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/egguy)


## WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/egguy/ha-addons/>


## About

Addons for HA, at the moment, mostly grott

## Installation

Use the following URL to add this repository:

```txt
https://github.com/egguy/ha-addons-edge
```

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fegguy%2Fha-addons-edge)



## Add-ons provided by this repository

### &#10003; [Grott Alpha branch (3.0)][addon-grott-beta]

![Latest Version][grott-beta-version-shield]
![Supports armhf Architecture][grott-beta-armhf-shield]
![Supports armv7 Architecture][grott-beta-armv7-shield]
![Supports aarch64 Architecture][grott-beta-aarch64-shield]
![Supports amd64 Architecture][grott-beta-amd64-shield]
![Supports i386 Architecture][grott-beta-i386-shield]

The Growatt inverter monitor with current HA plugin integrated

[:books: Grott Alpha branch (3.0) add-on documentation][addon-doc-grott-beta]

### &#10003; [Grott stable branch (2.8)][addon-grott]

![Latest Version][grott-version-shield]
![Supports armhf Architecture][grott-armhf-shield]
![Supports armv7 Architecture][grott-armv7-shield]
![Supports aarch64 Architecture][grott-aarch64-shield]
![Supports amd64 Architecture][grott-amd64-shield]
![Supports i386 Architecture][grott-i386-shield]

The Growatt inverter monitor with current HA plugin integrated

[:books: Grott stable branch (2.8) add-on documentation][addon-doc-grott]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant Community Add-ons [Discord Chat Server][discord]
- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Grott Alpha branch (3.0)][grott-beta-issue]
- [Open an issue for the add-on: Grott stable branch (2.8)][grott-issue]

For a general repository issue or add-on ideas [open an issue here][issue]



[addon-grott-beta]: https://github.com/egguy/addon-grott-beta/tree/4a9cb96
[addon-doc-grott-beta]: https://github.com/egguy/addon-grott-beta/blob/4a9cb96/README.md
[grott-beta-issue]: https://github.com/egguy/addon-grott-beta/issues
[grott-beta-version-shield]: https://img.shields.io/badge/version-4a9cb96-blue.svg
[grott-beta-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[grott-beta-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[grott-beta-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[grott-beta-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[grott-beta-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-grott]: https://github.com/egguy/addon-grott/tree/d56c723
[addon-doc-grott]: https://github.com/egguy/addon-grott/blob/d56c723/README.md
[grott-issue]: https://github.com/egguy/addon-grott/issues
[grott-version-shield]: https://img.shields.io/badge/version-d56c723-blue.svg
[grott-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[grott-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[grott-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[grott-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[grott-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[gitlabci-shield]: https://gitlab.com/egguy/ha-addons-edge/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/egguy/ha-addons-edge/pipelines
[issue]: https://github.com/egguy/ha-addons-edge/issues
[license-shield]: https://img.shields.io/github/license/egguy/ha-addons-edge.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2023.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html