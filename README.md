# pentmenu by centesis


Меню команд, позволяющее быстро и легко выполнять сканирование сети и DOS-атаки.

                                                                                       ███████████████████████████
                                        ds: centesis                                   ███████▀▀▀░░░░░░░▀▀▀███████
                                                                                       ████▀░░░░░░░░░░░░░░░░░▀████
                                                                                       ███│░░░░░░░░░░░░░░░░░░░│███
                                                                                       ██▌│░░░░░░░░░░░░░░░░░░░│▐██
                                                                                       ██░└┐░░░░░░░░░░░░░░░░░┌┘░██
                                tg: noupe                                              ██░░└┐░░░░░░░░░░░░░░░┌┘░░██
                                                                                       ██░░┌┘▄▄▄▄▄░░░░░▄▄▄▄▄└┐░░██
                                                                                       ██▌░│██████▌░░░▐██████│░▐██
                                                                                       ███░│▐███▀▀░░▄░░▀▀███▌│░███
                                                                                       ██▀─┘░░░░░░░▐█▌░░░░░░░└─▀██
                                                                                       ██▄░░░▄▄▄▓░░▀█▀░░▓▄▄▄░░░▄██
                         https://pastebin.com/u/centesis                               ████▄─┘██▌░░░░░░░▐██└─▄████                   
                                                                                       █████░░▐█─┬┬┬┬┬┬┬─█▌░░█████
                                                                                       ████▌░░░▀┬┼┼┼┼┼┼┼┬▀░░░▐████
                                                                                       █████▄░░░└┴┴┴┴┴┴┴┘░░░▄█████
                                                                                       ███████▄░░░░░░░░░░░▄███████
                                                                                       ██████████▄▄▄▄▄▄▄██████████
                                                                                       ███████████████████████████


# _Pentmenu — простой Bash-скрипт для разведки и DOS-атак_

## Зависимости：
                                                                                              
* bash

* sudo

* curl

* netcat

* hping3

* openssl

* stunnel

* nmap

* whois

* nslookup

* ike-scan

                                                               ┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼
                                                               ███▀▀▀██┼███▀▀▀███┼███▀█▄█▀███┼██▀▀▀
                                                               ██┼┼┼┼██┼██┼┼┼┼┼██┼██┼┼┼█┼┼┼██┼██┼┼┼
                                                               ██┼┼┼▄▄▄┼██▄▄▄▄▄██┼██┼┼┼▀┼┼┼██┼██▀▀▀
                                                               ██┼┼┼┼██┼██┼┼┼┼┼██┼██┼┼┼┼┼┼┼██┼██┼┼┼
                                                               ███▄▄▄██┼██┼┼┼┼┼██┼██┼┼┼┼┼┼┼██┼██▄▄▄
             thx for use)                                      ┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼
                                                               ███▀▀▀███┼▀███┼┼██▀┼██▀▀▀┼██▀▀▀▀██▄┼
                                                               ██┼┼┼┼┼██┼┼┼██┼┼██┼┼██┼┼┼┼██┼┼┼┼┼██┼
                                                               ██┼┼┼┼┼██┼┼┼██┼┼██┼┼██▀▀▀┼██▄▄▄▄▄▀▀┼
                                                               ██┼┼┼┼┼██┼┼┼██┼┼█▀┼┼██┼┼┼┼██┼┼┼┼┼██┼
               <3                                              ███▄▄▄███┼┼┼─▀█▀┼┼─┼██▄▄▄┼██┼┼┼┼┼██▄
                                                               ┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼██┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼██┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼████▄┼┼┼▄▄▄▄▄▄▄┼┼┼▄████┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼┼▀▀█▄█████████▄█▀▀┼┼┼┼┼┼┼┼┼┼
        https://discord.gg/nbclxn                              ┼┼┼┼┼┼┼┼┼┼┼█████████████┼┼┼┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼┼┼┼██▀▀▀███▀▀▀██┼┼┼┼┼┼┼┼┼┼┼┼
                 @sektadedsec                                  ┼┼┼┼┼┼┼┼┼┼┼██┼┼┼███┼┼┼██┼┼┼┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼┼┼┼█████▀▄▀█████┼┼┼┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼┼┼┼┼███████████┼┼┼┼┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼▄▄▄██┼┼█▀█▀█┼┼██▄▄▄┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼▀▀██┼┼┼┼┼┼┼┼┼┼┼██▀▀┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼┼┼▀▀┼┼┼┼┼┼┼┼┼┼┼▀▀┼┼┼┼┼┼┼┼┼┼┼
                                                               ┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼┼
 
## Download

- Шаг 1. Используйте следующую команду, чтобы установить инструмент в вашу операционную систему Kali Linux.
  
```
$ git clone https://github.com/centesis/pentmenu

```

- Шаг 3. Измените права доступа к файлу пентменю с помощью следующей команды.

```
$ chmod +x ./pentmenu

```

- Шаг 4. Запустите приведенную ниже команду, чтобы проверить установку.

```
$ ./pentmenu

```


git clone:

```
git clone https://github.com/centesis/pentmenu

```



# **Меню 1: Recon (модули распознавания)**

Это меню или модуль предлагает следующие функции:

Показать IP: этот параметр использует команду curl для поиска внешнего IP-адреса нашего компьютера.

Распознавание DNS: этот параметр нацелен на пассивное распознавание и, следовательно, выполняет поиск DNS и поиск цели в Whois.

Ping sweep: Этот параметр использует команду nmap для выполнения ICMP-эха (ping) для целевого хоста или сети.

Быстрое сканирование: этот параметр работает как сканер портов TCP, используя команду nmap для поиска открытых портов с помощью сканирования TCP SYN.

подробное сканирование: Этот параметр использует команду nmap для идентификации активных хостов, открытых портов, попыток идентификации операционной системы, записи баннеров и т. д.

UDP сканирование: Этот параметр использует команду nmap для поиска открытых портов UDP. Соответственно, сканирует все UDP-порты целевого хоста.

Проверить время работы сервера: этот параметр рассчитывает время безотказной работы целевого хоста, запрашивая открытый TCP-порт с помощью hping3. Точность результатов может варьироваться или может не работать от машины к машине.

Сканирование IPsec: этот параметр предназначен для попытки определить наличие сервера IPsec VPN с помощью ike-scan и различных предложений фазы 1.

# **Меню 2: DOS (модули атаки DOS)**

ICMP-эхо-флуд: этот вариант использует приложение командной строки hping3 для запуска традиционного эхо-флуда ICMP против целевого хоста.

ICMP Blacknurse Флуд: Этот вариант использует приложение командной строки hping3 для запуска традиционного ICMP-флуда Blacknurse против целевого хоста.

SYN-флуд TCP: Этот параметр отправляет поток пакетов TCP SYN, используя hping3. Но, да, если он не находит hping3, попробуйте вместо этого использовать утилиту nmap-nping.

Флуд TCP ACK: Этот параметр предлагает те же параметры, что и SYN Flood, но вместо этого устанавливает флаг TCP ACK (подтверждение).

RST-флуд TCP: Этот параметр предлагает те же параметры, что и SYN Flood, но вместо этого устанавливает флаг TCP RST (Reset).

TCP XMAS-флуд: Этот параметр предлагает те же возможности, что и SYN Flood и ACK Flood, но отправляет пакеты со всеми установленными флагами TCP (CWR, ECN, URG, ACK, PSH, RST, SYN, FIN).

Потоп UDP: Этот параметр предлагает те же возможности, что и SYN Flood, но вместо этого отправляет пакеты UDP на указанный хост: порт.

SSL ДВА: Этот параметр использует OpenSSL для попытки DOS-атаки на хост-порт назначения. Он делает это, открывая множество соединений и заставляя сервер выполнять дорогостоящие вычисления рукопожатия.

Slowloris: Этот параметр использует программу netcat для медленной отправки заголовков HTTP на целевой хост:порт с намерением лишить его ресурсов.

IPsec DOS: этот параметр использует программу ike-scan, чтобы попытаться залить указанный IP-адрес пакетами фазы 1 основного режима и агрессивного режима со случайных исходных IP-адресов.

Отвлечение-Сканирование: Этот параметр на самом деле он не запускает DOS-атаку, а просто запускает несколько SYN-сканирований TCP, используя hping3, с поддельного IP-адреса по нашему выбору.

# **Меню 3: Извлечение**

Отправить файл: Этот модуль использует программу netcat для отправки данных по протоколам TCP или UDP. что обычно чрезвычайно полезен для извлечения данных с целевых хостов.

Создать слушателя: Этот модуль использует netcat для открытия прослушивателя на настраиваемом порту TCP или UDP. Что обычно чрезвычайно полезно для тестирования подключения к системному журналу, получения файлов или проверки активного сканирования в сети.

И, наконец, **меню 4** (просмотреть файл Readme) Это позволяет нам увидеть локально и более подробно все, что описано выше, что, в свою очередь, находится на GitHub. И меню 5 (Выход), по сути, это выход и закрытие программы.

Donate: TQKxgZPDNbNfoVSfSBURrQ1McsRVFqMvSv (TRC20)

# **Связь со мной: ds - centesis**
