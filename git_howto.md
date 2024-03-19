# Подсказка по GIT

## Создние репозитория:
```sh
git init 
```
## Добавили индексацию:
```sh
git add "file_name"
```
## Зафиксировали commit:
```sh
git commit -m "commit_name"
```
## Просмотр всех коммитов в развёрнутом виде:
```sh
git log
```
## Просмотр всех коммитов в удобном виде:
```sh
git log --oneline 
```
## Просмотр всех коммитов в удобном виде c веточными изменениями:
```sh
git log --oneline --graph
```
## Переход между commitами:
```sh
git checkout "first_six_commit's_number"
```
## Отображение всех веток:
```sh
git branch
```
## Создание новой ветки:
```sh
git branch "new_branch_name"
```
## Удаление ветки:
```sh
git brach -d "name_branch"
```
## Переход между ветками 
```sh
git checkout "branch_name"
```
## Слияние веток
### *__Нельзя слить с веткой на которой вы находитесь!__*
```sh
git merge "branch_name"
```
## Локальная копия удалённого репозитория
```sh
git clone "URL.git"
```
## Стягивание всех изменений удалённого репозитроия в локальный
```sh
git pull
```
## Выгрузка всех изменений локального репозитория в удалённый
```sh
git push
```




