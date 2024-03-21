# GIT. Руководство пользователя

## Что такое GIT?
*GIT - это система контроля версий, которая позволяет отслеживать изменения исходного кода и управлять ими*

![GIT](imp.png)

### Основные команды
```sh
git init - инициализирует локальный репозиторий
```
```sh
git add - добавляет содержимое рабочего каталога
```
```sh
git commit - фиксирует или сохраняет содержимое
```
```sh
git log - показывает журнал изменений
```
```sh
git git checout - переключает между версиями
```
```sh
git diff - показывает разницу между текущим файлом и сохраненным
```

### Основные команды для работы с ветками

```sh
git branch - показывает все ветки и активную на текущий момент
```
```sh
git branch /name/ - создает новую ветку
```
```sh
git checkout - позволяет переключаться между ветками. Вводим git checkout /name/
```
```sh
git merge - позволяет объединить ветки. Вводим git merge /name/
```
```sh
git branch -d - позволяет удалить ветку. Вводим branch -d /name/
```
### Синтаксис языка Markdown
* жирный текст — *,

* курсивный текст — *,

* зачеркнутый текст — ~,

* выделяют заголовки — # в начале строки,

* показать уровень заголовка —
подчеркивание знаками = или ****,

* нумерованные списки — обозначаются
обычными цифрами 1, 2, 3,

* ненумерованные списки — обозначаются
*знаками в начале строки,

* вложенные списки — выполняем отступы.

### Основные команды для работы с удаленным репозиторием

```sh
git push - передача данных из локального репозитория в удаленный,
```
```sh
git pull - позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией 
```
