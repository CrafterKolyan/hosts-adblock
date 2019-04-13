[Перейти к русской версии (Go to russian version)](#Russian-version)
# hosts AdBlock

This repository contains `hosts` file which blocks most advertisements over the internet

## Installation

### Windows
Copy `hosts` file to `C:\Windows\System32\drivers\etc\`.

### Linux & Unix & Mac OS
Copy `hosts` file to `/etc/hosts`.

### Other system
You can find location of `hosts` file in your operating system via [Wikipedia](https://en.wikipedia.org/wiki/Hosts_\(file\)#Location_in_the_file_system).
Replace `hosts` file with the one in the repository.

## How is it working?
`hosts` file sets the connection between an IP addresses and domain names.
Each line in `hosts` file consists of two parts. First part is an IP address, second is a domain name.
Example:

> 204.71.200.67 yahoo.com

In the example we associate domain name `yahoo.com` with IP address `204.71.200.67`.
It means that any time when we try to access `yahoo.com` we will be automatically redirected to 
IP address `204.71.200.67`.

`hosts` file in this repository redirects a lot of domain names containing advertisements to
IP address `0.0.0.0` which is
a non-routable meta-address used to designate an invalid, unknown or non applicable target.
                    
# Russian version
# hosts AdBlock
Этот репозиторий содержит в себе файл `hosts`, который блокирует большое количество рекламных объявлений в интернете.

## Установка

### Windows
Скопировать файл `hosts` в папку `C:\Windows\System32\drivers\etc\`.

### Linux & Unix & Mac OS
Скопировать файл `hosts` в `/etc/`.

### Other system
Вы можете найти местоположение файла `hosts` для своей операционной системы при помощи [Википедии](https://en.wikipedia.org/wiki/Hosts_\(file\)#Location_in_the_file_system).
Замените файл `hosts` файлом из репозитория.

## Как это работает?
Файл `hosts` устанавливает связи между IP адресами и доменными именами.
Каждая строка файла `hosts` состоит из двух частей. Первая часть - IP адрес, вторая - доменное имя.
Пример:

> 204.71.200.67 yahoo.com

В данном примере мы ассоциируем доменное имя `yahoo.com` с IP адресом `204.71.200.67`.
Это означает, что каждый раз, когда мы будем обращаться по имени `yahoo.com` мы будем автоматически
перенаправлены на IP адрес `204.71.200.67`.

Файл `hosts` из данного репозитория перенаправляет множество доменных имён, содержащих рекламу, на IP адрес
`0.0.0.0`, который является немаршрутизируемым мета-адресом, используемым для обозначения недопустимой, неизвестной или не применимой цели.