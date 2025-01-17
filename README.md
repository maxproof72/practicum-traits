# practicum-traits

Данный репозиторий хранит мои шпаргалки для работы с git, GitHub и MD-файлами

Пока все эти шпаргалки хранятся в одном файле, но я предполагаю их разделить.

## GIT

### remote
``` bash
git remote add origin git@github.com:/repo  # привязка удаленного репозитория к локальному
git remote -v   # проверка связи репозиториев
```
Работа с удаленными репозиториями

### clone

``` bash
git clone git@github.com:/repo
```
Клонирование репозитория на локальный компьютер


### add

``` bash
git add -all                        # добавление в индекс всех файлов из папки
git add filename                    # добавление указанного файла в индекс
git add filename1 filename2 ...     # добавление заданных файлов в индекс
```
Добавление одного или нескольких файлов в индекс

### commit

``` bash
git commit -?                       # запрос справки
git commit                          # выполнение коммита (с запросом описания)
git commit -a                       # включение в индекс измененных файлов и выполнение коммита
git commit -m 'Commit title'        # выполнение коммита с заданным описанием
```
Выполнение коммита

### push

``` bash
git push    # отправка изменений на удаленный репозиторий
git push -u origin master  # отправка данных и связывание локальной ветки и удаленной. Если удаленной ветви нет, она создается
```
Отправка данных на уделенный репозиторий

### pull
``` bash
git pull    # загрузка изменений с сервера
```
Загрузка изменений удаленного репозитория

### config traits

``` bash
git config --global core.editor "nano"  # замена vim на nano
```
Некоторые настройки git


## GIT HUB

### fork
Создание независимой копии внешнего репозитория в собственном аккаунте


## MD

Шпаргалка перенесена в отдельный файл - см. [файл](https://github.com/maxproof72/practicum-traits/blob/main/markdown-cheat-sheet.md)

