# Nginx configuration file

Учебный репозиторий по курсу **Devops**, раздел *Git*.

## 1. Описание

В этом репозитории находится кофигурационный файл популярного веб сервера [nginx](http://nginx.com)

## 2. Nginx.conf

### 2.1 Кусочек конфига nginx

```
# Load dynamic modules. See /usr/share/nginx/README.dynamic.
include /usr/share/nginx/modules/*.conf;

events {
    worker_connections 1024;
    } 
```
### 2.2 Запуск nginx

```bash
$ systemctl start nginx
```

Тестирование конфигурационного файла `nginx -t`. Конфиг должен находится в `/etc/nginx`.

## 3. Полезные ссылки

- [Работа с удаленными репозиториями](https://git-scm.com/book/ru/v1/Основы-Git-Работа-с-удалёнными-репозиториями)
- [Гайд по markdown](https://guides.github.com/features/mastering-markdown)
