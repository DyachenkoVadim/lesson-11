##Задание: добавьте все файлы в локальное хранилище;
Команда: git app . 

##Задание: создайте новую ветку и перейдите в неё;
Команды: git barnch <branch-name> (Создание ветки)
        git checkout <branch-name> (Переход на созданную ветку)


##Задание: загрузите на удаленный репозиторий лишь основную ветку вашего проекта.

Команды: git checkout master (Переход на осоновную ветку)
        git remote add origin https://github.com/DyachenkoVadim/lesson-11.git (Запись удаленного репозитория)
        git push -u origin master (Запись на удаленный репозиторий ветки master)