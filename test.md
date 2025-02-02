# Инструкция по работе с GIT - ом

Чтобы создать репозиторий, мы используем команду:  
> **git init** - создает локальный репозиторий

Чтобы сохранить файл в репозитории, мы используем команду: 
>1. **git add filename** - сохранить файл с именем filename в репозитории
>2. **git add .** - сохранить **АБСОЛЮТНО** все файлы в вашем репозитории

Чтобы получить информацию от git-а о его текущем состоянии, мы используем команду:  
> **git status**  

Чтобы создать коммит, мы используем команду:  
> **git commit -m “message”**

Чтобы осуществить вывод на экран истории всех коммитов с их хеш-кодами, мы используем команду:  
> **git log**

Чтобы переходить от одного коммита к другому, мы используем команду:  
> **git checkout**

Чтобы вернуться к актуальному состоянию и продолжить работу, мы используем команду:  
> **git checkout master**

Чтобы увидеть разницу между текущим файлом и закоммиченным файлом, мы используем команду:
> **git diff**

# Семинар 2
## Ветвления в git:  

Чтобы посмотреть список веток в репозитории, мы используем команду:
> **git branch**   

Чтобы создать новую ветку, мы используем команду:
> **git branch name_branch**

Чтобы перейти к другой ветке, мы используем команду:
> **git checkout name_branch**  

Чтобы удалить ветку после слияния, мы используем команду:
> **git branch -d name_branch**

Чтобы изменить старое название ветки на новое, мы используем команду:
> **git branch -m old_branch_name new_branch_name**  

Чтобы слить две ветки вместе, мы используем команду:
> **git merge name_branch**

Чтобы вывести список коммитов в виде графика, мы используем команду:
> **git log --graph**

# Семинар 3
## Работа в GitHub, pull request
Чтобы склонировать репозиторий, мы используем команду:  
> **git clone**  

Чтобы отправить локальную версию репозитория на внешний репозиторий, мы используем команду:
> **git push**

Чтобы получить изменения и слить с локальной версией, мы используем команду:
> **git pull**