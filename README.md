# Git from PyCharm <br>

---
## Описание:

Работа с Git в PyCharm.

> Итоговая работа сливалась с помощью pull request в ветку develop (ветка разработки)

Условия домашки
Ваш первый день на работе. Тимлид обсудил с вами план на день и попросил выполнить следующие задачи. Помните, что вы работаете по GitFlow.

---
## Реализация:

## Задание 1. Получение проекта <br>
### Выполните следующие шаги: <br>

**На GitHub:**
1) Создайте новый репозиторий с файлом readme.md.
2) Создайте ветку develop. <br>

**Локально:**
3) Клонируйте репозиторий с GitHub на компьютер.
4) Откройте проект в PyCharm (3-й и 4-й пункт можно сразу сделать из PyCharm).
5) Сделайте checkout удаленной ветки develop (станет текущей).
6) Создайте, заполните и закоммитьте файл .gitignore.
> Подумайте, какие файлы надо игнорировать при работе из PyCharm. Важно, чтобы лишние файлы, которые создает PyCharm, не попадали в коммиты.
7) Отправьте изменения на GitHub. <br>

## Задание 2. Первый пул-реквест <br>
### Выполните следующие шаги: <br>

1) Создайте и переключитесь на ветку feature/Task2.
2) Создайте файл str_func.py и в нем функцию, которая принимает на вход строку и возвращает ее со всеми заглавными буквами.
3) Закоммитьте проделанную работу и отправьте изменения на GitHub. <br>

**На GitHub:**
4) Сделайте pull request из ветки feature/Task2 в develop.
> После pull request вашему тимлиду приходит уведомление. Он смотрит, что было сделано, вносит комментарии, отклоняет или принимает пул-реквест.
В учебных целях действия тимлида вы делаете самостоятельно.

5) Сделайте за тимлида мердж с удалением ветки feature/Task2. <br>

**Локально:**
6) Удалите локальную ветку feature/Task2.
7) Обновите локальную ветку develop. <br>

## Задание 3. Наращивание функционала <br>
> Тимлид дал задачу написать еще одну функцию и попросил не забывать добавлять описание к функциям (
docstring).

### Выполните следующие шаги: <br>

**На GitHub:**
1) Добавьте docstring к функции из предыдущего задания (прямо в ветке develop). Этим вы сымитируете проделанную работу другого разработчика над этим же модулем. <br>

**Локально:**
2) Напишите в файле str_func.py вторую функцию, которая делает заглавными первые буквы каждого слова в строке, поступившей на вход функции. Добавьте к функции docstring.
> Помните, что вы работаете по GitFlow. Разработка в ветке main и develop не ведется. Изменения туда попадают только через pull request. Что это значит для выполнения этого задания?

3) Добавьте docstring к функции из Задания 2.
4) Отправьте проделанную работу коллегам на код-ревью (т. е. pull-request, который должен показать, что есть конфликт: This branch has conflicts that must be resolved).


## Задание 4. Решение конфликтов <br>
> Ваш пул-реквест не прошел, так как есть конфликт. Другой программист уже внес описание к вашей первой функции, пока вы работали над второй.

### Выполните следующие шаги: <br>

1) Подтяните изменения в ветку develop (у вас должны появиться правки другого программиста).
2) Сделайте мердж develop в текущую ветку, где вы ведете разработку (вам предложат порешать конфликт).
3) Решите конфликт, отклонив описание функции другого программиста.
4) Сделайте пуш.
5) За тимлида заапрувьте пул-реквест на GitHub.
