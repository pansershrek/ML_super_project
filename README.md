## Инструкция по пользованию git для нашей команды.

## Ссылка на наш репозиторий
https://github.com/pansershrek/ML_super_project

## Установка необходимых программных компонентов
```
sudo apt-get install git
```

## Настройка git, где неободимо заменить "you@example.com" и "Your Name" на свои соответственно
```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

## Клонирование репозитория на локальную машину
```
git clone https://github.com/pansershrek/ML_super_project.git
```

## Для каждого участника нашей команды, существует своя ветка репозитория. На первых этапах проэкта предпологается, что он будет работать независимо от других участников команды. Ветку master пока не трогаем.

## Проверка статуса репозитория
```
git status
```

## Обновляем свой репозиторий
```
git pull
```

## Для переключения на свою ветку, где имя соответственно Gleb, Lena, Anna, Roma
```
git checkout Name
```

# Для добавления и загрузки изменений репозитория, необходимо:

## Добавить изменения файлов
```
git add File1, File2, ... FileN
```

## Коментируем изменения
```
git commit -m "Your commit"
```

## Загружаем изменения, где Name имя вашей ветки, то есть соответственно Gleb, Lena, Anna, Roma
```
git push origin Name
```
