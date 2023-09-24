<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Rportd for YunoHost

[![Integration level](https://dash.yunohost.org/integration/rportd.svg)](https://dash.yunohost.org/appci/app/rportd) ![Working status](https://ci-apps.yunohost.org/ci/badges/rportd.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/rportd.maintain.svg)

[![Install Rportd with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rportd)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Rportd quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Rport helps you to manage your remote servers without the hassle of VPNs, chained SSH connections, jump-hosts, or the use of commercial tools like TeamViewer and its clones.


**Shipped version:** 0.9.0~ynh1

## Screenshots

![Screenshot of Rportd](./doc/screenshots/screenshot.png)

## Disclaimers / important information

### :red_circle: Rportd has been closed-sourced and its code repository deleted.

Installations will fail and no more updates will be made to the app. You need to find an alternative.

For more information: https://github.com/realvnc-labs/rport/blob/192d76724b43fd52a95892174b63a1f45153d77f/README.md

## Documentation and resources

* Official app website: <https://rport.io/>
* Official admin documentation: <https://kb.rport.io/>
* Upstream app code repository: <https://github.com/cloudradar-monitoring/rport>
* YunoHost documentation for this app: <https://yunohost.org/app_rportd>
* Report a bug: <https://github.com/YunoHost-Apps/rportd_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/rportd_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/rportd_ynh/tree/testing --debug
or
sudo yunohost app upgrade rportd -u https://github.com/YunoHost-Apps/rportd_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
