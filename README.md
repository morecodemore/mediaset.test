#Описание работы с проектом

**Установка и запуск*

Для работы и вотчинга проекта на вашей машине должен быть установлен глобально сборщик Gulp:

`$ npm install --global gulp-cli`

Далее необходимо установить зависимости проекта:

`npm install`

***Если есть проблемы при установке, необходимо выполнить последовательно следующие команды для обновления пакета:*

`npm i -g npm-check-updates`

`npm-check-updates -u`

`npm install`

Далее выполняем следующую команду, которая запускает процесс сборки проекта:

`gulp`

###Важно!
Для корректной работы процесса сборки необходимо располагать все файлы .html в папке _source, т.к. Gulp забирает их именно из этой папки.


В конце работы с проектом рекомендуется удалить папку _assets и запустить сборщик повторно.
