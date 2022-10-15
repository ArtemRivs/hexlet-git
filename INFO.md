<h2>Main block #1</h2>
<p>Text of main block #001</p>
<p>Text of main block #002</p>
<p>Text of main block #003</p>

<h2>Main block #2</h2>
<p>Text of main block #001</p>
<p>Text of main block #002</p>
<p>Text of main block #003</p>

https://githowto.com/ru/more_setup
HEAD detached from e08fae6


Перейдите в рабочий каталог

Перейдите в рабочий каталог и сделайте клон вашего репозитория hello.
Выполните:

cd ..
pwd
ls

Примечание: Сейчас мы находимся в рабочем каталоге.
Результат:

$ cd ..
$ pwd
/Users/alex/Documents/Presentations/githowto/auto
$ ls
hello

В этот момент вы должны находиться в «рабочем» каталоге. Здесь должен быть единственный репозиторий под названием «hello».
02
Создайте клон репозитория hello

Давайте создадим клон репозитория.
Выполните:

git clone hello cloned_hello
ls

Результат:

$ git clone hello cloned_hello
Cloning into cloned_hello...
done.
$ ls
cloned_hello
hello


$ git branch -a
* master
  remotes/origin/HEAD -> origin/master
  remotes/origin/style
  remotes/origin/master

Git выводит все коммиты в оригинальный репозиторий, но ветки в удаленном репозитории не рассматриваются как локальные. Если мы хотим иметь собственную ветку style, мы должны сами ее создать. Через минуту вы увидите, как это делается.
