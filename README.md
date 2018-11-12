## Инструкция по пользованию git для нашей команды.

# Ссылка на наш репозиторий
https://github.com/pansershrek/ML_super_project

# Установка необходимых программных компонентов
```
sudo apt-get install git
```

# Настройка git, где неободимо заменить "you@example.com" и "Your Name" на свои соответственно
```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

## Клонирование репозитория на локальную машину
```
git clone https://github.com/pansershrek/ML_super_project.git
```

## Для каждого участника нашей команды, существует своя ветка репозитория. На первых этапах проэкта предпологается, что он будет работать независимо от других участников команды. Ветку master пока не трогаем.

# Проверка статуса репозитория
```
git status
```

# Для переключения на свою ветку, где имя соответственно Gleb, Lena, Anna, Roma
```
git checkout Name
```