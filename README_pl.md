<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Cjdns dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/cjdns)](https://ci-apps.yunohost.org/ci/apps/cjdns/)
![Status działania](https://apps.yunohost.org/badge/state/cjdns)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/cjdns)

[![Zainstaluj Cjdns z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Cjdns na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**Dostarczona wersja:** 22.7~ynh2

## Zrzuty ekranu

![Zrzut ekranu z Cjdns](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Repozytorium z kodem źródłowym: <https://github.com/cjdelisle/cjdns/>
- Sklep YunoHost: <https://apps.yunohost.org/app/cjdns>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
lub
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
