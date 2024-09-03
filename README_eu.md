<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Cusdis YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/cusdis.svg)](https://ci-apps.yunohost.org/ci/apps/cusdis/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/cusdis.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/cusdis.maintain.svg)

[![Instalatu Cusdis YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cusdis)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Cusdis YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Cusdis is an open-source, lightweight (~5kb gzip), privacy-friendly alternative to Disqus.

###Features

- Lightweight comment widget, with i18n, dark mode.
- Email notification
- Webhook
- Easy to self-host
- Many integrations


**Paketatutako bertsioa:** 1.3.0~ynh1

**Demoa:** <https://demo.example.com>

## Pantaila-argazkiak

![Cusdis(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://cusdis.com/>
- Administratzaileen dokumentazio ofiziala: <https://cusdis.com/doc#/self-host/manual>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/djyde/cusdis>
- YunoHost Denda: <https://apps.yunohost.org/app/cusdis>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/cusdis_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing --debug
edo
sudo yunohost app upgrade cusdis -u https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
