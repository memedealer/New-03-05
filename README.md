# Первые шаги по освоениею HTML

##Инструкция по запуску проекта

1. Скачиваем Vagrant и VirtualBox

1. Клонируем репозиторий в удобную нам паппку с помощью команды:

        git clone git@github.com:memedealer/New-03-05.git
 1. Переходим в папку **cd New-03-05** 
 1. Запускаем Виртуальную машину: `vagrant up`
 1. Захожим в командную строку виртуальной машины по SSH-протоколу: vagrant ssh
 ## Инструкция по базовой работе с GIT
 
 1. `git add` - добавляет файл в индекс
 1. `git commit` - создает коммит из всех файлов в индексе 
 1. `git commit -m "Comment"` - позволяет добавить комментарий к коммиту в командной строке
 1. `git push` -  залить изменения в удаленный репозиторий
 1. `git pull` - принять изменения с удаленного репозитория 
 1. `git clone  git@github.com:useer/reponame.git` - склонировать удаленный репозиторий
 

 

 
 ## Работа с HTML
 
 ### Подключение скриптов и стилей
 
 * Скрипты можно подключить с помощью тега `<script>`:
         <script type ="text/javascript"> 
         // объясвляем переменную j и присваиваем 
         console.log(j);
         </script>
                  
 * Стили создаются с помощью тега `<style>`:                  
        <style></style>
        
 ### ПОдключение файлов
 
 * Чтобы подключить скриптовый файл, нелбходимо прописать тег `<script>` с атрибутом `src` `<script src=">` :
     <script src="/index.js" type="text/javascript"></script>
     
 * Для подключения файла со стилями прописываем тег `<link>` с атрибутом `rel="stylesheet"`:
        <link rel="stylesheet" href="index.css">
 
        