### Тестовый репозиторий

## Как использовать Git в связке с GitHub

### Авторизация

```bash
git config --global user.name 'Ваше имя'
git config --global user.email адрес-почты-без-кавычек
git config --list
```

Чтобы выйти из режима просмотра, нажмите `Q`

### Временно убрать написанный код (спрятать изменения до коммита)

```bash
git stash
```

### Вернуть код обратно

```bash
git stash apply
```

### Проверка созданных веток

```bash
git branch
```
