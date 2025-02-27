Сугубо копия, не каких притязаний на авторство не имею

# [Открыть UVMOD](https://uvmod.valek.net.ru/)
## [Открыть оригинальный UVMOD (английский)](https://whosmatt.github.io/uvmod/)
## [中文版 Открыть Китайскую версию (поддерживается отдельно)](https://uvmod.xanyi.eu.org/)
## [Открыть Португальскую версию (поддерживается отдельно)](https://meshtastic.pt/QuanSheng/)

### Инфо по v26/v27

UVMOD основывается на v26, поскольку новая версия прошивки v27 не приносит никаких важных исправлений, кроме небольшого фикса, затрагивающего небольшое количество устройств.  
В зависимости от заводской калибровки некоторых раций, мощность передачи выше 435МГц может быть ниже, чем должна быть из-за программной ошибки.  
v27 исправляет этот момент так, что мощность более не проседает.
Для проверки затрагивает ли вашу рацию эта проблема необходимо использовать измеритель мощности или другой приёмник с показателем RSSI. Если мощность в режиме L выше, чем
мощность в режиме H то это именно эта проблема.

На данный момент поддержка v27 есть только в Португальской и Русской версии UVMOD.  

Оригинальные разработчики, также, работают над переносом фикса в v26.

## Introduction

Веб-версия патчера прошивок от Quansheng и Веб-прошивальщик написанный на Javascript и HTML, используя [Bootstrap 4.6.0](https://getbootstrap.com/docs/4.6/getting-started/introduction/), jQuery и частично тему [SB Admin 2 Theme](https://startbootstrap.com/theme/sb-admin-2).  
Основано на данных от множества людей [uvmod-kitchen](https://github.com/amnemonic/Quansheng_UV-K5_Firmware/tree/main/uvmod_kitchen) и воплощает ту же функциональность в модульном виде на javascript. 

Посетители могут сгенерировать изменённую на основе выбранных патчей прошивку. Пачти изменяют прошивку в двоичном виде и могут настраиваться на основе запросов пользователя. Файл-основа для прошивки может быть использована своя для включения модов, которые уже вшиты в существующую прошивку.  
Сгенерированная прошивка может быть сразу прошита, если используется поддерживаемый браузер. Дополнительное ПО не требуется. 

## Отношение к небезопасным клонам UVMOD

Радиосвязь используется различными людьми и организациями, некоторые из которых важны для обеспечения работы критической инфраструктуры. Модификация прошивки должна производиться с пониманием и учётом возможных последствий.  
UVMOD позволяет легко и удобно каждому неподготовленному пользователю изменять прошивку собственной рации. __Однако, некоторые моды, такие как Разблокировка передачи везде, не могут быть использованы легально и безопасно при отсутствии определённых знаний и понимания принципов работы радио, ввиду контринтуитивного поведения в результате.__  
UVMOD скрывает опасные моды в информационном разделе инструкции, чтобы убедиться, что пользователь был предупреждён о возможных последствиях.  
