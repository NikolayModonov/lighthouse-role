# Lighthouse Role

Роль для установки и настройки LightHouse (Nginx + статика).

## Переменные

| Переменная | Значение по умолчанию | Описание |
|------------|-----------------------|----------|
| lighthouse_archive_url | https://github.com/VKCOM/lighthouse/archive/refs/heads/master.zip | Ссылка на архив |
| lighthouse_install_dir | /var/www/lighthouse | Директория установки |
| nginx_port | 80 | Порт для Nginx |

## Пример использования

```yaml
- hosts: lighthouse
  roles:
    - lighthouse
```