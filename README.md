﻿# Установка доверия к сертификатам для разработки под ASP.NET Core

## Для Windows
Выполнить из под администратора `win-dev-certs-registration.cmd`

_Не забудьте перезагрузить ваше веб-приложение и браузер, если они были запущены_


## Для MacOS
Выполнить в терминале  
`sudo ./mac-dev-certs-registration.sh`

_Не забудьте перезагрузить ваше веб-приложение и браузер, если они были запущены_


## Для Ubuntu Linux
Выполнить в терминале  
`sudo ./ubuntu-linux-dev-certs-registration.sh`

_Особенность Linux в том, что нет единого глобального места для хранения доверенных сертификатов._
_Скрипт выше полагается на наличие apt, а сертификат устанавливается для Chromium (но не для Firefox)._

_Не забудьте перезагрузить ваше веб-приложение и браузер, если они были запущены_