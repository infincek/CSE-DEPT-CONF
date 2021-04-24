---
key: change_data_capture_in_production
title: Change Data Capture in production 
language: Français
level: advanced
speakers:
  - yann_pauly
  - david_morin
format: conference
draft: false
tags:
  - _big_data___ml___ai
---
OVH, 18 ans d’existence, est aujourd’hui le 1er cloud provider européen. Pour suivre et piloter son business, OVH a mis en place un datalake interne. L’idée étant de centraliser l’ensemble des données issues de plusieurs milliers de tables localisées dans ses différents datacentres pour ensuite générer les KPIs utiles au business. Le point essentiel est que ces données doivent être mises à jour continuellement. Cette présentation décrit le pipeline actuellement en production et les différentes itérations. Depuis la collecte des données via les “binary logs” au niveau des bases de données, jusqu'à l’écriture en continu (streaming) dans Apache Hive sur un cluster Hadoop Kerberisé basé sur Openstack. Pour cela nous nous sommes aidés de Apache Flink, solution de streaming devenue incontournable. Nous expliquerons comment nous avons géré la conversion de schéma et le cycle de vie des messages au sein du pipeline grâce à ce framework (Watermarks, State, Window aggregation, …).
