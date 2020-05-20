# install-hook

Скрипт загрузки и установки хука [prepare-commit-msg](https://github.com/Davert94/prepare-commit-msg)

## Цель скрипта

Устанавливает хук _prepare-commit-msg_ в текущий репозиторий git'а.
Если до этого уже существовал данный хук, то он переименовывается в резервный (например, _prepare-commit-msg.reserve_).

## Установка и выполнение

```bash
$ cd <repository_dir>
$ wget -qO - https://raw.githubusercontent.com/Davert94/install-hook/master/install-hook.sh | bash

// Или если wget не установлен в системе
$ curl -s https://raw.githubusercontent.com/Davert94/install-hook/master/install-hook.sh | bash
```
