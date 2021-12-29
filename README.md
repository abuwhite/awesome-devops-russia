# Awesome DevOps Ru

[![CI](https://github.com/znhv/awesome-devops/actions/workflows/main.yaml/badge.svg)](https://github.com/znhv/awesome-devops/actions/workflows/main.yaml)

Кураторский список для DevOps-инженера 
с актуальной и понятной 📚 документацией.

- [Языки программирования](#языки-программирования) - Go, Python, Ruby, Node.js, Rust, C, C++.
- [Аспекты операционных систем](#аспекты-операционных-систем) - Управление процессами, виртуализация и файловая система.
- [Администрирование серверов](#администрирование-серверов) - Ubuntu, CentOS, RHEL, FreeBSD.
- [Сеть и безопасность](#Сеть-и-безопасность) - Протоколы транспорта, сертификаты, шифрование и модели сетевого взаимодействия.
- [Веб-сервера](#Веб-сервера) - Nginx, Apache, IIS, Tomcat, Caddy.
- [Инфраструктура как код](#инфраструктура-как-код) - Система контроля версий, контейнеры, оркестрация, управление конфигурацией и инфраструктурой.
- [Непрерывная доставка или непрерывное развертывание](#непрерывная-доставка-или-непрерывное-развертывание) - Gitlab CI, Jenkins, Github Actions, Circle CI, Travis CI, Bamboo, Teamcity, Azure DevOps.
- [Мониторинг инфраструктуры и приложения](#Мониторинг-инфраструктуры-и-приложения) - Управление логами, мониторинг инфраструктуры и приложений.
- [Облачные платформы](#облачные-платформы) - AWS, Google Cloud, Azure, Yandex Cloud, Digital Ocean, Heroku, Linode, Vultr.
- [Остальное](#остальное) - Алгоритмы, веб-разработка, фронтенд и собеседование.
- [База данных](#база-данных) - Redis, MongoDB, MySQL, PostgreSQL.
- [Книги](#книги)
- [Научные статьи](#scientific-papers)
- [Другие Ресурсы](#other-resources)
- [Внесите свой вклад](#Внесите-свой-вклад)
- [Лицензия](#лицензия)

## Языки программирования
- [Go](https://github.com/avelino/awesome-go#readme)
- [Python](https://github.com/vinta/awesome-python#readme) — General-purpose programming language designed for readability.
- [Ruby](https://github.com/markets/awesome-ruby#readme)
- [JavaScript](https://github.com/sorrycc/awesome-javascript#readme)
- [Rust](https://github.com/rust-unofficial/awesome-rust#readme)
- [C](https://github.com/inputsh/awesome-c#readme)
- [C++](https://github.com/fffaraz/awesome-cpp#readme) — General-purpose language with a bias toward system programming and embedded, resource-constrained software.

## Аспекты операционных систем
- [Управление процессами](https://doka.guide/tools/process-management/) - Про управление процессами в многопоточных операционных системах.
- [Потоки и параллелизм](https://russianblogs.com/article/86971326826/) - Поток, процесс и параллелизм.
- [Сокеты](https://habr.com/ru/company/otus/blog/539550/) - Сокеты в ОС Linux.
- [Основы POSIX](https://blog.iteducenter.ua/articles/chto-takoe-posix/) - Что такое POSIX?
- Основы компьютерных сетей 
  - [Тема №1. Основные сетевые термины и сетевые модели](https://habr.com/ru/post/307252/)
  - [Тема №2. Протоколы верхнего уровня](https://habr.com/ru/post/307714/)
  - [Тема №3. Протоколы нижних уровней (транспортного, сетевого и канального)](https://habr.com/ru/post/308636/)
  - [Тема №4. Сетевые устройства и виды применяемых кабелей](https://habr.com/ru/post/312340/)
  - [Тема №5. Понятие IP адресации, масок подсетей и их расчет](https://habr.com/ru/post/314484/)
  - [Тема №6. Понятие VLAN, Trunk и протоколы VTP и DTP](https://habr.com/ru/post/319080/)
  - [Тема №7. Протокол связующего дерева: STP](https://habr.com/ru/post/321132/)
  - [Тема №8. Протокол агрегирования каналов: Etherchannel](https://habr.com/ru/post/334778/)
  - [Тема №9. Маршрутизация: статическая и динамическая на примере RIP, OSPF и EIGRP](https://habr.com/ru/post/335090/)
- [Работа с сетью]()
- [Управление инициализацией (initd)]()
- Управление сервисами (systemd)
  - [Systemd за пять минут](https://habr.com/ru/company/southbridge/blog/255845/)
  - [Шпаргалка по управлению сервисами CentOS 7 с systemd](https://habr.com/ru/company/infobox/blog/241237/)
  - [Systemd: пишем собственные .service и .target](https://habr.com/ru/post/275645/)
- [Управление вводом/выводом]()
- [Виртуализация]()
- [Память/Диск]()
- [Файл и файловые системы]()

## Администрирование серверов
- Операционная система
  - Linux
    - [Интерфейс командной строки](os/linux/cli/index.md)
    - [Многозадачность и процессы](os/linux/multitasking-and-processes/index.md)
    - [Вопросы по Linux](os/linux/questions.md)
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
  - Сеть — nmap, tcpdump, ping, mtr, traceroute, dlg, airmon, airodump, dig, iptables, netstat
  - Мониторинг процессов — ps, top, htop, atop, lsof 
  - Производительность системы — nmon, iostat, sar, vmstat
  - Работа с текстом — awk, sed, grep, sort, uniq, cat, cut, echo, fmt, tr, nl, egrep, fgrep, wc
  - Bash-скрипт
  - Vim/Nano/PowerShell/Emacs
  - Компиляция
  - Другие — strace, dtrace, systemtap, uname, df, history

## Сеть и безопасность
- HTTP
  - [Протокол HTTP](network/http-protocol/index.md)
- HTTPS
- FTP
- SSL/TLS
  - [SSL-сертификаты](network/ssl-certificates/index.md)
- TCP и UDP
  - [Протоколы TCP и UDP](network/tcp-udp-protocols/index.md)
- SSH
  - [Доступ по SSH](os/linux/ssh/index.md)
- Перенаправление портов
- DNS
- Модель OSI
  - [Модели сетевого взаимодействия](network/network-models/index.md)
  - [Шифрование](network/encoding/index.md)
  - [Вопросы](network/questions.md)

## Веб-сервера
- Nginx
- Apache
- IIS
- Tomcat
- Caddy

## Инфраструктура как код
- Система контроля версий
  - [Git](https://git-scm.com/book/ru/v2/Введение-Что-такое-Git%3F) - Что такое Git?
  - [Git How To](https://githowto.com/ru) - Интерактивный тур, который познакомит с основами Git.
  - [Вопросы](vcs/git/questions.md)
- Контейнеры
  - Docker
    - [Что такое Docker](virtualization/docker/index.md)
    - [Мультиконтейнерное приложение и Docker Compose](virtualization/docker/docker-compose/index.md)
    - [Управление данными в Docker](virtualization/docker/docker-data-management/index.md)
    - [Как устроен Dockerfile](virtualization/docker/dockerfile/index.md)
    - [Вопросы](virtualization/docker/questions.md)
  - LXC
- Управление конфигурацией
  - Ansible
    - [Что такое Ansible](ansible/index.md)
    - [Вопросы](ansible/questions.md)
  - Chef
  - Salt
  - Puppet
- Оркестрирование контейнеров
  - Kubernetes
    - [Вопросы](orchestration/kubernetes/questions.md)
  - Docker Swarm
  - Mesos
  - Nomad
- Управление инфраструктурой
  - Terraform
    - [Вопросы](orchestration/terraform/questions.md)
  - CloudFormation
  - Pulumi
- Service Mesh
  - Consul
  - Istio
  - Linkerd
  - Envoy

## Непрерывная доставка или непрерывное развертывание
- Gitlab CI
- Jenkins
- Github Actions
- Circle CI
- Travis CI
- Bamboo
- Teamcity
- Azure DevOps
  - [Вопросы](questions.md)

## Мониторинг инфраструктуры и приложения
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
- AWS
- Google Cloud
- Azure
- Yandex Cloud
- Digital Ocean
- Heroku
- Linode
- Vultr

## База данных

## Остальное
- Алгоритмы, структуры
  - [Вопросы](algorithms/questions.md)
- Веб-разработка
  - [Веб-разработка](other/web/questions.md)
- Фронтенд
  - [Вопросы](other/frontend/questions.md)
- Собеседование
  - [Вопросы работодателю](other/hr/index.md)

## Книги

## Внесите свой вклад
Чтобы поддерживать репозиторий в актуальном состоянии, 
каждый может ✨ [внести свой вклад в проект](contributing.md).

## Лицензия
![license](https://badgen.net/badge/license/MIT/green)