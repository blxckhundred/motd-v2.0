<p aling="center"><a href="https://github.com/distillium/motd">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="./media/logo.png" />
   <source media="(prefers-color-scheme: light)" srcset="./media/logo-black.png" />
   <img alt="distillium/motd" src="https://github.com/distillium/motd" />
 </picture>
</a></p>

Кастомная система приветственного сообщения для серверов **Debian/Ubuntu** с расширенной информацией о системе и безопасным управлением.

<details>
<summary>🌌 Предпросмотр MOTD</summary>

![screenshot](./media/preview.png)

</details>

## Возможности
- Отображение информации о системе
- Информация о безопасности: статус брандмауэра и доступные обновления пакетов
- Мониторинг Docker контейнеров
- Надежная установка с полной системой резервного копирования
- Простое управление через интерактивное меню `motd-set`

## Резервное копирование и безопасность
- Автоматический бэкап ключевых конфигурационных директорий и файлов
- Восстановление системы при удалении MOTD или ошибках установки

## Установка/обновление (root):
```
curl -fsSL https://raw.githubusercontent.com/blxckhundred/motd-v2.0/refs/heads/main/install-motd.sh | bash
```
or
```
curl -fsSL https://raw.githubusercontent.com/blxckhundred/motd-v2.0/refs/heads/main/install-motd.sh | sudo bash
```

## Для удаления используйте:
`motd-set` и выберите соответсвующий пункт

## Команды:
- `motd` — ручной вызов MOTD
- `motd-set` — открыть интерактивное меню настроек
