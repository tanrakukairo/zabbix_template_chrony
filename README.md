# zabbix_template_chrony

Chrony NTP Client Template for Zabbix ~> 3.4.

Necessary "Dependent Item". Put userparameter_chrony.conf in Include-UserParameter's Directory.

- ZABBIX 3.4用 Chrony NTPクライアントのテンプレートです。
- UserParameterのワインライナーでTrackingをJSON化して、依存アイテムで各値を入れてます。
- FreeBSD11/CentOS7.1以上で動きます。

このテンプレートはMIT Licenseです。
