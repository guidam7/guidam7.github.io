# guidam7.github.io

# Сетевая диагностика

Нечеткое описание проблемы. Всегда нужен ip адрес - откуда и куда, время когда наблюдалась проблема
>- traceroute
>- mtr
>- looking glass

# Управление серверами
>- ZTP - zero toch provisioning
>- dhcppython
>- netbox
>- vnstat
>- zabbix


# Traffic generation
>- функциональные тесты
>- тесты производительности
>- отказоустойчивость
>- проверка заявленный скейлингов
>- проверка работы фильтров
-----------------------------------------------------
>- tcprelay - проверка работы обоурдования на близком к реальном трафике. Проверка работы детектора атак
>- iperf - проверка пропускной способности, проверка производительности (простые пакеты, клиент-серверное)
>- hping3 - проверка фильтров и файерволов
>- fping - проверка вермени перерыва сервиса в топологиях с большим количеством связей
>- macof - проверка ограничения максимального количества МАС-адресов на порту
>- arping - проверка лимитов ARP
>- trafgen - универсальный инструмент для генерации любых пакетов
>- mirotik traffic generator - универсальный инструмент для генерации любых пакетов
>- scapy - питоновский модуль. Генерация любых пакетов, оценка ответа сетевого устройства, сниффинг трафика, режим отправки и получения. 
>- trex - Циско - генерация любых пакетов, оценка ответа сетевого устройства на отправленные пакеты, нагрузочное тестирование. Использует dpdk. Поддерживает формат scapy

RFC 9411 Методология тестирования сетевых устройств
