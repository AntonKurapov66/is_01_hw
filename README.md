# Домашнее задание к занятию "Уязвимости и атаки на информационные системы" - `Курапов Антон`

## Задание 1
* Скачайте и установите виртуальную машину Metasploitable: https://sourceforge.net/projects/metasploitable/.
* Это типовая ОС для экспериментов в области информационной безопасности, с которой следует начать при анализе уязвимостей.
* Просканируйте эту виртуальную машину, используя nmap.
* Попробуйте найти уязвимости, которым подвержена эта виртуальная машина.(Сами уязвимости можно поискать на сайте https://www.exploit-db.com/.)
* Ответьте на следующие вопросы:

  *  Какие сетевые службы в ней разрешены?
![alt text](https://github.com/AntonKurapov66/is_01_hw/blob/main/img/1_1.PNG)
  *  Какие уязвимости были вами обнаружены? (список со ссылками: достаточно трёх уязвимостей)
   1. https://www.exploit-db.com/exploits/32849 (PostgreSQL 8.3.6 - Conversion Encoding Remote Denial of Service)
   2. https://exploit-db.com/exploits/37723 (ISC BIND 9 - TKEY Remote Denial of Service (PoC))
   3. https://www.exploit-db.com/exploits/23245 (Apache Tomcat 4.0.x - Non-HTTP Request Denial of Service)

## Задание 2
* Проведите сканирование Metasploitable в режимах SYN, FIN, Xmas, UDP.
* Запишите сеансы сканирования в Wireshark.
* Ответьте на следующие вопросы:

  *  Чем отличаются эти режимы сканирования с точки зрения сетевого трафика?
  *  Как отвечает сервер?

