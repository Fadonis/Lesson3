# **Инструкция по работе с GIT**

# Создание нового локального репозитория
Для создания нового репозитория надо набрать

    git init

# Git add
Для добавления изменений в коммит используется
    
     git add <тия файда> 
     git commit -m "comment"

# Проверка состояния репозитория
Вывод статуса
  
    git status

Вывод изменений

    git log 
    git log --oneline
    git log --graph
    git --all для просмотра всех веток

# Создание новой ветки
Иначе все будет в main ветке

    git branch - просмотр существующих веток
    git branch <название_ветки>

    #или вот так

    git checkout -b <название_ветки>

 # Удаление ветки

    git branch -d <name>

# Залитие изменений в master

    # Переключаемся в master
    git checkout master
    # Обновляем локальную ветку с сервера
    git pull origin master

    Делаем слияние текущей ветки и указанной
    git merge <название_ветки>

## Просмотр различий

    git diff <name1><name2>

# Вставка изображений
![Snake img](img/snake.jpg)
   # " ![Snake img](img/snake. jpg) "

#DZ
   Creation new branch
   log view
   Creation messege in branch Vetka2
   abra-kadabra