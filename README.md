**Задание 1**

1. Установите программу iReasoning MIB Browser (или аналогичную) на свой ПК.

2. С помощью snmpwalk запросите все доступные данные у хоста:

IP: 45.134.127.23

SNMP READ Community: netology_snmp


**Решение 1**

![Image alt](https://github.com/mezhibo/ni0902/blob/e3c2d2813d69359c741ad5c6a9c2beb8750c8eb3/IMG/11.jpg)



**Задание 2**

1. Установите Zabbix на виртуальную машину.

2. Добавьте хост для мониторинга со следующими параметрами:

Имя: netology_csr

Адрес SNMP: 45.134.127.23

SNMP Community: netology_snmp

3. Прикрепите к хосту встроенный в заббикс шаблон Cisco IOS versions 12.0._3_T-12.2_3.5 by SNMP.

4 Подождите 2 минуты и перейдите в Latest data по хосту netology_csr.


**Решение 2**

![Image alt](https://github.com/mezhibo/ni0902/blob/e3c2d2813d69359c741ad5c6a9c2beb8750c8eb3/IMG/2.jpg)


![Image alt](https://github.com/mezhibo/ni0902/blob/aab1caefd322ec94ff07180694dc694191ee4d91/IMG/4.jpg)
