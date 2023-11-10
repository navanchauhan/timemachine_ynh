<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Time Machine for YunoHost

[![Integration level](https://dash.yunohost.org/integration/timemachine.svg)](https://dash.yunohost.org/appci/app/timemachine) ![Working status](https://ci-apps.yunohost.org/ci/badges/timemachine.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/timemachine.maintain.svg)

[![Install Time Machine with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=timemachine)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Time Machine quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Package to create a Time Machine Backup Source

### Features

- Automatically detected by Time Machine
- Integrated with YunoHost's Backups
- Supports multiple installs

**Shipped version:** 1.0~ynh5

## Screenshots

![Screenshot of Time Machine](./doc/screenshots/example.jpg)

## Documentation and resources

* Official app website: <https://support.apple.com/en-us/HT201250>
* Upstream app code repository: <https://github.com/YunoHost-Apps/timemachine_ynh>
* YunoHost Store: <https://apps.yunohost.org/app/timemachine>
* Report a bug: <https://github.com/YunoHost-Apps/timemachine_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/timemachine_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/timemachine_ynh/tree/testing --debug
or
sudo yunohost app upgrade timemachine -u https://github.com/YunoHost-Apps/timemachine_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
