---
title: "Usługi działające na bramce"
sidebar_label: Usługi bramki
---


## Usługi działające na bramce

Na bramce standardowo działają następujące usługi:

Nazwa         | Protokół | Porty | Komenda/URL                                                          | Opis
----          | ----     | ------- | -------                                                            | -----------
 Aplikacja AIS| http     | **80** / `8180`  | [http://ais-dom.local](http://ais-dom.local)              | serwer http
 FTP          | ftp      | **21** / `1024`  | [ftp://ais-dom.local](ftp://ais-dom.local)                | serwer ftp
 SSH          | ssh      | **22** / `8022`  | ```ssh ais-dom```                                         | serwer ssh
 MQTT         | mqtt     | **1883**         | ```mosquitto_sub -h ais-dom.local -t '#'```               | serwer mqtt
 Terminal     | http     | **8888**         | [http://ais-dom.local:8888](http://ais-dom.local:8888)    | powłoka bash w aplikacji webowej
 Zigbee2Mqtt  | http     | **8099**         | [http://ais-dom.local:8099](http://ais-dom.local:8099)    | aplikajca zigbee2mqtt
 Rest API     | http     | **8122**         | [http://ais-dom.local:8122](http://ais-dom.local:8122)    | api bramki


## Przydatne linki

Linki do usług działających na bramce oraz inne przydatne linki dostępne są z aplikacji, wystarczy w menu wybrać opcję **Przydatne linki**

![Przydatne Linki](/img/en/bramka/ais_gate_links.png)
