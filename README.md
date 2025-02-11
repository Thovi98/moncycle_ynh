<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Moncycle for YunoHost

[![Integration level](https://dash.yunohost.org/integration/moncycle.svg)](https://dash.yunohost.org/appci/app/moncycle) ![Working status](https://ci-apps.yunohost.org/ci/badges/moncycle.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/moncycle.maintain.svg)

[![Install Moncycle with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=moncycle)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Moncycle quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Menstrual cycle follow-up for natural family planning

**Shipped version:** 7.0~ynh4

**Demo:** https://tableau.moncycle.app/connexion.php?email1=demo@moncycle.app&mdp=demo

## Screenshots

![Screenshot of Moncycle](./doc/screenshots/moncycle_app.png)

## Disclaimers / important information

* No LDAP integration
* After installing, you can create your own user using the form
* Once done, you can (if you want) set the account creation to false in `/var/www/moncycle_app/config.php`
* If you want to use the app in PWA mode, be sure to be connected to your account first

## Documentation and resources

* Official app website: <https://moncycle.app>
* Upstream app code repository: <https://github.com/jean-io/moncycle.app>
* YunoHost documentation for this app: <https://yunohost.org/app_moncycle>
* Report a bug: <https://github.com/YunoHost-Apps/moncycle_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/moncycle_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/moncycle_ynh/tree/testing --debug
or
sudo yunohost app upgrade moncycle -u https://github.com/YunoHost-Apps/moncycle_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
