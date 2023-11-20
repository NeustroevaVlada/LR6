# LR6
Лабораторная работа №6

**Цель работы:** изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

**Ход работы**
1.  Аккаунт github был создан до выполнения работы (ссылка - https://github.com/NeustroevaVlada)
2.  Сделана копия в личное хранилище (Fork). 
3.  Установила Git.
4.  Настроила конфигурации, а именно имя пользователя (Группа Фамилия И.О.) и email.

![](/forLR6/start.jpg)

5.  Клонировала удалённый репозиторий.

![](/forLR6/clone.jpg)

6.  Добавила файл через интерфейс GitHub. Подтянула изменения в локальный репозиторий.

![](/forLR6/create.jpg)

![](/forLR6/pull.jpg)

7.  Получила историю операций для каждой из веток.

Для master

![](/forLR6/logmaster.jpg)

Для branch1

![](/forLR6/logbranch.jpg)

8.  Просмотрела последние изменения.

![](/forLR6/status.jpg)

9.  Выполнила слияние в ветку master, разрешив конфликт.

Слияние веток

![](/forLR6/mergeconflict.jpg)

Конфликт решен с помощью графического интерфейса.

![](/forLR6/VIM.jpg)

![](/forLR6/mergeok.jpg)

Зафиксированы изменения

![](/forLR6/fix.jpg)

10. Удалила побочную ветку после успешного слияния локально и глобально.

Глобально

![](/forLR6/del.jpg)

11. Сделала изменения и зафиксировала их, оставляя комментарии. 

![](/forLR6/edit1.jpg)

![](/forLR6/edit2.jpg)

12. Сделала откат коммита.

![](/forLR6/reset.jpg)

13. Создала вету для отчета.

![](/forLR6/new.jpg)

14. Начала оформлять отчёт в файле README.md

![](/forLR6/startreport.jpg)

15. Получила историю операций в форматированном виде.

![](/forLR6/fin.jpg)

## Лог команд

```
    $ cd ../LR6/
    $ git clone https://github.com/NeustroevaVlada/LR6
    $ git pull
    $ git branch -l
    $ git log
    $ git checkout branch1
    $ git merge branch1
    $ git mergetool
    $ git status
    $ git add .
    $ git commit -m "conflicte resolution"
    $ git commit -m "add TestFile2"
    $ git commit -m "edit TestFile"
    $ git commit -m "edit TestFile"
    $ git reset --hard HEAD~
    $ git checkout -b report
    $ git log --pretty="%h %ad %an %s" 
```
####
