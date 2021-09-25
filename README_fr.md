# Facette pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/facette.svg)](https://dash.yunohost.org/appci/app/facette) ![](https://ci-apps.yunohost.org/ci/badges/facette.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/facette.maintain.svg)  
[![Installer Facette avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=facette)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Facette rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Facette is a web application to display time series data from various sources — such as collectd, Graphite, InfluxDB or KairosDB — on graphs, designed to be easy to setup and to use.

**Version incluse :** 0.5.1~ynh1

**Démo :** https://play.facette.io/browse/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://facette.io/
* Documentation officielle de l'admin : https://docs.facette.io/
* Dépôt de code officiel de l'app : https://github.com/facette/facette
* Documentation YunoHost pour cette app : https://yunohost.org/app_facette
* Signaler un bug : https://github.com/YunoHost-Apps/facette_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/facette_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
ou
sudo yunohost app upgrade facette -u https://github.com/YunoHost-Apps/facette_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps