# Git

## Основные команды Git

Все глобальные настройки Git хранит в файле `.gitconfig` в домашней директории. Команда запишет в этот файл указанные имя и почту. 

```bash
git config --global user.name "deathcriding" 
git config --global user.email babaev.daniil.r@gmail.com
```

Для создания директории git необходимо выполнить команду

```bash
git init
```

Чтобы “разгитить” директорию необходимо выполнить команду

```bash
rm -rf .git
```

Проверить состояние репозитория 

```bash
git status
```

Для отслеживания необходимо добавить файлы

```bash
git add . # добавить всю текущую папку
git add best.py # добавить один файл
```

Для комита необходимо выполнить команду 

```bash
git commit -m "I am the best"
```

Привязать удалённый репозиторий к локальному

```bash
git remote add origin git@github.com:Deathcriding/education.git
```

Убедиться, что репозитории связаны

```bash
 ****git remote -v
```

Чтобы запушить данные необходимо выполнить команду

```bash
git push -u origin master
```

## Генерация ключей

```bash
$ ssh-keygen -t ed25519 -C "babaev.den@gmail.com"
```

## Readme.md
