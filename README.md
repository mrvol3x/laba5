# Топология
![топология](https://github.com/mrvol3x/laba5/blob/main/topology.png)
# Настройка hostname для Свитчей
|SW1|SW2|SW3|
| --- | --- | --- |
|```enable``` |```enable``` |```enable``` |
| ```conf t```|```conf t```|```conf t```|
|hostname SW1|hostname SW2| hostname SW3|
|```do copy running-config startup-config```|```do copy running-config startup-config```|```do copy running-config startup-config```|

# Настройка hostname для роутеров
|R1|R2|
| --- | --- |
|en|en      |
|cofn t|conf t|
|hostname R1|hostname R2|
|do copy running-config st|do copy running-config st|

# Настройка vlan и ip для vlan

|SW1|SW2|SW3|
| --- | --- | --- |
|en|en|en|
|conf t| conf t|conf t|
|vlan 100|vlan 100|vlan 100,110,120|
|int vlan 100|int vlan 100|int vlan 100,110,120|
|name LAN100|name LAN 100|name LAN 100,110,120|
|no shutdown|no shutdown|no shutdown|
|ip adddress ip и маска сети|ip adddress ip и маска сети|ip adddress ip и маска сети|
|do copy running-config st|do copy running-config st|do copy running-config st|

# Настройка имени домена для всех устройств 
|ip domain-name jun14.wsr|
| --- |

# Настройка пароля и пользователя c полным доступом для устройств
|en|
|---|
|conf t|
|username jun14 privilege 15 secret P@ssw0rd|
|enable password wsr|
