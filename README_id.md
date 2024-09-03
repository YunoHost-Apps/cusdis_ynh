<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Cusdis untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/cusdis.svg)](https://ci-apps.yunohost.org/ci/apps/cusdis/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/cusdis.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/cusdis.maintain.svg)

[![Pasang Cusdis dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cusdis)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Cusdis secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Cusdis is an open-source, lightweight (~5kb gzip), privacy-friendly alternative to Disqus.

###Features

- Lightweight comment widget, with i18n, dark mode.
- Email notification
- Webhook
- Easy to self-host
- Many integrations


**Versi terkirim:** 1.3.0~ynh1

**Demo:** <https://demo.example.com>

## Tangkapan Layar

![Tangkapan Layar pada Cusdis](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://cusdis.com/>
- Dokumentasi admin resmi: <https://cusdis.com/doc#/self-host/manual>
- Depot kode aplikasi hulu: <https://github.com/djyde/cusdis>
- Gudang YunoHost: <https://apps.yunohost.org/app/cusdis>
- Laporkan bug: <https://github.com/YunoHost-Apps/cusdis_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing --debug
atau
sudo yunohost app upgrade cusdis -u https://github.com/YunoHost-Apps/cusdis_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
