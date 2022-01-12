# Awesome DevOps Ru

[![CI](https://github.com/znhv/awesome-devops/actions/workflows/main.yaml/badge.svg)](https://github.com/znhv/awesome-devops/actions/workflows/main.yaml)

Кураторский список для DevOps-инженера 
с актуальной и понятной 📚 документацией.

- [Аспекты операционных систем](#аспекты-операционных-систем)
- [Администрирование серверов](#администрирование-серверов)
- [Сеть и безопасность](#Сеть-и-безопасность)
- [Веб-сервера](#Веб-сервера)
- [Языки программирования](#языки-программирования)
- [Инфраструктура как код](#инфраструктура-как-код)
- [Непрерывная доставка или непрерывное развертывание](#непрерывная-доставка-или-непрерывное-развертывание)
- [Мониторинг инфраструктуры и приложения](#Мониторинг-инфраструктуры-и-приложения)
- [Облачные платформы](#облачные-платформы)
- [База данных](#база-данных)
- [Ресурсы](#ресурсы)
  - [Книги](#книги)
  - Научные статьи
  - [Собеседование](#собеседование)
  - [Алгоритмы](#алгоритмы)
- [Внесите свой вклад](#Внесите-свой-вклад)
- [Лицензия](#лицензия)

## Языки программирования
_Go, Python, Ruby, Node.js, Rust, C, C++._

- Go
- [Python](https://www.python.org) - высокоуровневый язык программирования общего назначения с динамической строгой типизацией и автоматическим управлением памятью.
- Ruby
- JavaScript
- Rust
- C
- C++

## Аспекты операционных систем
_Управление процессами, виртуализация и файловая система._

- [Управление процессами](https://doka.guide/tools/process-management/) - Про управление процессами в многопоточных операционных системах.
- [Потоки и параллелизм](https://russianblogs.com/article/86971326826/) - Поток, процесс и параллелизм.
- [Сокеты](https://habr.com/ru/company/otus/blog/539550/) - Сокеты в ОС Linux.
- [Основы POSIX](https://blog.iteducenter.ua/articles/chto-takoe-posix/) - Что такое POSIX?
- Основы компьютерных сетей 
  - [Основные сетевые термины и сетевые модели](https://habr.com/ru/post/307252/)
  - [Протоколы верхнего уровня](https://habr.com/ru/post/307714/)
  - [Протоколы нижних уровней (транспортного, сетевого и канального)](https://habr.com/ru/post/308636/)
  - [Сетевые устройства и виды применяемых кабелей](https://habr.com/ru/post/312340/)
  - [Понятие IP адресации, масок подсетей и их расчет](https://habr.com/ru/post/314484/)
  - [Понятие VLAN, Trunk и протоколы VTP и DTP](https://habr.com/ru/post/319080/)
  - [Протокол связующего дерева: STP](https://habr.com/ru/post/321132/)
  - [Протокол агрегирования каналов: Etherchannel](https://habr.com/ru/post/334778/)
  - [Маршрутизация: статическая и динамическая на примере RIP, OSPF и EIGRP](https://habr.com/ru/post/335090/)
- Работа с сетью
- Управление инициализацией (initd)
- Управление сервисами (systemd)
  - [Systemd за пять минут](https://habr.com/ru/company/southbridge/blog/255845/)
  - [Шпаргалка по управлению сервисами CentOS 7 с systemd](https://habr.com/ru/company/infobox/blog/241237/)
  - [Systemd: пишем собственные .service и .target](https://habr.com/ru/post/275645/)
- Управление вводом/выводом
- Виртуализация
  - [Что такое виртуализация и как работает виртуальный сервер](https://habr.com/ru/company/vps_house/blog/344048/) 
- Память/Диск
- Файл и файловые системы

## Администрирование серверов
_Ubuntu, CentOS, RHEL, FreeBSD._

- Операционная система
  - Linux
  - Ubuntu
  - CentOS
  - RHEL
  - Fedora
  - Debian
  - SUSE Linux
  - Unix
  - FreeBSD
  - OpenBSD
  - NetBSD
  - Windows
- Терминал
  - Сеть 
    - [nmap](https://habr.com/ru/post/131433/) - Руководство для начинающих.
    - [tcpdump](https://habr.com/ru/company/first/blog/335428/) - Давайте изучим tcpdump с Джулией Эванс.
    - [ping](https://habr.com/ru/company/cbs/blog/322386/) - Ping и некоторые его параметры.
    - mtr
    - [traceroute](https://losst.ru/komanda-traceroute-linux) - Команда traceroute Linux.
    - dlg
    - airmon
    - airodump
    - dig
    - iptables
      - [Настройка iptables для чайников](https://losst.ru/nastrojka-iptables-dlya-chajnikov)
      - [Основы iptables на примере Debian глазами младенца](https://habr.com/ru/sandbox/18975/)
    - netstat
      - [Netstat, где мои дейтаграммы?](https://habr.com/ru/post/312710/)
    - ss
      - [Первое знакомство с командой ss](https://habr.com/ru/company/ruvds/blog/346744/)
  - Мониторинг процессов
    - ps
    - top
    - htop
    - atop
    - lsof
  - Производительность системы
    - nmon
    - iostat
    - sar
    - vmstat
  - Работа с текстом
    - awk
    - sed
    - grep
    - sort
    - uniq
    - cat
    - cut
    - echo
    - fmt
    - tr
    - nl
    - egrep
    - fgrep
    - wc
  - Bash-скрипт
  - Vim/Nano/PowerShell/Emacs
  - Компиляция
  - Другие
    - strace
    - dtrace
    - systemtap
    - uname
    - df
    - history

## Сеть и безопасность
_Протоколы транспорта, сертификаты, шифрование и модели сетевого взаимодействия._

- HTTP
  - [Протокол HTTP](https://doka.guide/tools/http-protocol/)
- HTTPS
  - [Что такое протокол HTTPS, и как он защищает вас в интернете](https://guides.hexlet.io/https-yandex-guide/) 
- FTP
- SSL/TLS
  - [SSL-сертификаты](https://doka.guide/tools/ssl-certificates/)
- TCP/UDP
  - [Протоколы TCP и UDP](https://doka.guide/tools/tcp-udp-protocols/)
- SSH
  - [Доступ по SSH](https://doka.guide/tools/ssh/)
- Перенаправление портов
- DNS
  - [Что такое DNS-сервер простыми словами](https://guides.hexlet.io/dns/)
- Модель OSI
  - [Модели сетевого взаимодействия](https://doka.guide/tools/network-models/)
  - [Шифрование](https://doka.guide/tools/encoding/)

## Веб-сервера
_Nginx, Apache, IIS, Tomcat, Caddy._

- Nginx
  - [Веб-сервер Nginx](https://doka.guide/tools/nginx-web-server/)
- Apache
  - [Веб-сервер Apache](https://doka.guide/tools/apache-web-server/)
- IIS
- Tomcat
- Caddy

## Инфраструктура как код
_Система контроля версий, контейнеры, оркестрация, управление конфигурацией и инфраструктурой._

- Система контроля версий
  - [Git](https://git-scm.com/book/ru/v2/Введение-Что-такое-Git%3F) - Что такое Git?
  - [Git How To](https://githowto.com/ru) - Интерактивный тур, который познакомит с основами Git.
- Контейнеры
  - Docker
    - [Что такое Docker](https://doka.guide/tools/docker/)
    - [Как и для чего использовать Docker](https://guides.hexlet.io/docker/)
    - [Мультиконтейнерное приложение и Docker Compose](https://doka.guide/tools/docker-compose/)
    - [Управление данными в Docker](https://doka.guide/tools/docker-data-management/)
    - [Как устроен Dockerfile](https://doka.guide/tools/dockerfile/)
  - LXC
- Управление конфигурацией
  - Ansible
    - [Пособие по Ansible](https://habr.com/ru/post/305400/)
    - [Основы Ansible, без которых ваши плейбуки — комок слипшихся макарон](https://habr.com/ru/post/508762/)
  - Chef
  - Salt
  - Puppet
- Оркестрация контейнеров
  - Kubernetes
  - Docker Swarm
  - Mesos
  - Nomad
- Управление инфраструктурой
  - Terraform
  - CloudFormation
  - Pulumi
- Service Mesh
  - Consul
  - Istio
  - Linkerd
  - Envoy

## Непрерывная доставка или непрерывное развертывание
_Gitlab CI, Jenkins, Github Actions, Circle CI, Travis CI, Bamboo, Teamcity, Azure DevOps._

- Gitlab CI
- Jenkins
- Github Actions
- Circle CI
- Travis CI
- Bamboo
- Teamcity
- Azure DevOps

## Мониторинг инфраструктуры и приложения
_Управление логами, мониторинг инфраструктуры и приложений._

- Управление логами
  - Elastic Stack
  - Graylog
  - Splunk
  - Papertrail
- Мониторинг приложений
  - Jaeger
  - New Relic
  - AppDynamics
  - Instana
  - OpenTracing
- Мониторинг инфраструктуры
  - Prometheus
  - Grafana
  - Nagios
  - Zabbix
  - Monit
  - Datadog

## Облачные платформы
_Публичные и частные облачные платформы._

- [Amazon Web Services (AWS)](https://aws.amazon.com/) - Публичное облако.
- [Google Cloud Platform (GCP)](https://cloud.google.com/) - Облачная платформа.
- [Azure](https://azure.microsoft.com/) - Облачные вычисления.
- [Yandex Cloud](https://cloud.yandex.com/) - Публичная облачная платформа.
- [Digital Ocean](https://www.digitalocean.com/) - помогает разработчикам легко создавать, тестировать, управлять и масштабировать приложения любого размера.
- Heroku
- Linode
- Vultr

## База данных
_Redis, MongoDB, MySQL, PostgreSQL._

## Ресурсы
### Книги
- [Unix и Linux: руководство системного администратора. 5-е изд.](https://www.ozon.ru/product/unix-i-linux-rukovodstvo-sistemnogo-administratora-5-e-izd-340602675/?sh=g_dFBE17) - Эви Немет, Гарт Снайдер, Трент Хейн, Бэн Уэйли, Дэн Макин.
- [Kubernetes в действии](https://www.ozon.ru/product/kubernetes-v-deystvii-luksha-marko-217051241/?sh=ujzog6h4) - Лукша Марко.
- [Continuous delivery. Практика непрерывных апдейтов]() - Эберхард Вольф.
- [Философия DevOps. Искусство управления IT]() - Дженнифер Дэвис.
- [Проект «Феникс». Роман о том, как DevOps меняет бизнес к лучшему]() - Джун Ким, Джонг Хан Ким, Бер К., Спаффорд Д.
- [Руководство по DevOps]() - Джин Ким, Патрик Дебуа, Джон Уиллис и Джез Хамбл.
- [Site Reliability Engineering. Надежность и безотказность как в Google]() - Бетси Бейер, Крис Джоунс, Дженнифер Петофф.

### Алгоритмы
- Алгоритмы, структуры

### Собеседование
_Вопросы для подготовки_

- [Linux - Basic](https://github.com/rmntrvn/adm_linux_ops_questions/blob/master/questions/linux.basic.md)
- [Linux - Main+](https://github.com/rmntrvn/adm_linux_ops_questions/blob/master/questions/linux.basic.md)
- [Docker](https://github.com/rmntrvn/adm_linux_ops_questions/blob/master/questions/docker.md) 
- [Ansible](https://github.com/rmntrvn/adm_linux_ops_questions/blob/master/questions/ansible.md) 
- [Kubernetes](https://github.com/rmntrvn/adm_linux_ops_questions/blob/master/questions/kubernetes.md)
- [Terraform](https://github.com/rmntrvn/adm_linux_ops_questions/blob/master/questions/terraform.md)
- Вопросы работодателю

## Внесите свой вклад
Чтобы поддерживать репозиторий в актуальном состоянии, 
каждый может ✨ [внести свой вклад в проект](contributing.md).

## Лицензия
![license](https://badgen.net/badge/license/MIT/green)