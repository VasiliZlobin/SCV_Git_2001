# Работа с Git

## Проверка наличия установленного Git

Выполнить в терминале следующую команду:
```
git --version
```
Если Git в наличии, то покажет версию Git, иначе будет сообщение об ошибке.

## Установка Git

[Установщик Git для OS X доступен для скачивания с сайта Git https://git-scm.com/download/mac](https://git-scm.com/download/mac)

## Настройка Git

При первом использовании Git необходимо представиться. Для этого выполните команды установки адреса электронной почты и имени пользователя:
```
git config --global user.email ваша_почта@example.com
git config --global user.name «Ваше имя англ буквами»
```
## Работа с Git

### Инициализировать Git в рабочем каталоге
Для этого перейдите в рабочий каталог и выполните команду 
```
git init
```
 Внутри рабочего каталога будет создан подкаталог ".git".

 ### Проверить статус
 ```
 git status
 ```

Пример результата:
```
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   Git_instructions.md 

no changes added to commit (use "git add" and/or "git commit -a")
```

### Посмотреть изменения
```
git diff
```
Пример результата:
![Скриншот](diff_image.png)