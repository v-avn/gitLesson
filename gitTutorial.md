# This is my Git Tutorial

* *git init* - добавление репозитория

1. Создание новой ветки и переходы между ветками
* *git branch* - просмотр всех веток
* *git branch ИМЯ_ВЕТКИ* - создание ветки ИМЯ_ВЕТКИ
* *git checkout ИМЯ_ВЕТКИ* - переход на ветку ИМЯ_ВЕТКИ

2. Слияние веток
* *git merge ИМЯ_ВЕТКИ* - сливаем ветку ИМЯ_ВЕТКИ в текущую

3. Конфликты
* Fast-forward
* Auto-merge ORT
* Бывают безконфликтные слияния и бывают конфликтные, которые требуют ручного решения

4. Итоги

тестовая строка

тестовый pull request

Valeria

test_fork

## Homework Bykov Mihail

1. на сайте делаем **fork** (ответвление) интересующего нас репозитория
2. делаем копию своей версии репозитория - **git clone http://**
3. переходим на нужную папку - **cd .\fail_name**
4. создаем новую ветку и делаем ее активной - **git checkout -b branch_name**, либо **git branch branch_name** и **git checkout branch_name**
5. вносим свои изменения в файл только в этой ветке
6. фиксируем изменения - **git add** и **git commit -m**
7. отправляем свою версию в GitHub - **git push --set-upstream origin branch_name**
8. на сайте GitHub нажимаем кнопку **Compare and pull request**
9. добавляем комментарий (при необходимости) и жмем **Create pull request**