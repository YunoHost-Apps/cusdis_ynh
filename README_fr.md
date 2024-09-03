<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Cusdis pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/cusdis.svg)](https://ci-apps.yunohost.org/ci/apps/cusdis/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/cusdis.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/cusdis.maintain.svg)

[![Installer Cusdis avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cusdis)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Cusdis rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Cusdis est une alternative open source, légère (~5 ko gzip) et respectueuse de la vie privée à Disqus.

###Fonctionnalités

- Widget de commentaire léger, avec i18n, mode sombre.
- Notification par e-mail
- Webhook
- Facile à auto-héberger
- Nombreuses intégrations


**Version incluse :** 1.3.0~ynh1

## Captures d’écran

![Capture d’écran de Cusdis](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://cusdis.com/>
- Documentation officielle de l’admin : <https://cusdis.com/doc#/self-host/manual>
- Dépôt de code officiel de l’app : <https://github.com/djyde/cusdis>
- YunoHost Store : <https://apps.yunohost.org/app/cusdis>
- Signaler un bug : <https://github.com/YunoHost-Apps/cusdis_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing --debug
ou
sudo yunohost app upgrade cusdis -u https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
