1. Как скопировать на свой компьютер репозиторий из github.com, что должно быть сделано предварительно?

 - Предварительно должен быть создан репозиторий на github.
 - В терминале перейти в каталог, в который надо скопировать репозиторий. 
 - Использовать команду git clone "ссылка на репозиторий".


Как создать git репозиторий из локального каталога на своем компьютере. Как его отправить на github.com?

- git init создать пустой репозиторий
- git add . 
- git commit -m 'new' сохранить изменения (выполнить коммит)
- Создание нового репо на GitHub
- git remote add origin <ссылка> выполнить привязку LOCAL ↔ REMOTE
- git push -u origin master выгрузить на GitHuв
    1. git push -u origin main
    2. git push
    3. git push -u -f origin main

Как получить на локальный компьютер изменения с github.com
- С помощью команды "git pull"

Какую информацию нам дают команда :

git status - позволяет получить информацию о состоянии локального репозитория Git, текущую ветку,  список измененных файлов в рабочем каталоге, список файлов, которые находятся в рабочем каталоге, но не отслеживаются Git.

git log - предоставляет информацию о коммитах в Git репозитории: Хэш, Автор: Имя и электронная почта, Дата и время создания коммита, Описание изменений, сделанных в данном коммите.

git remote -v - список связанных удаленных репозиториев.

# TelRunGit