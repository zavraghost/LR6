# LR6
Лабораторная работа №6
# Отчёт по выполнению лабораторной работы

# 1. Цель работы

Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт 
работы с локальным и удаленным репозиторием.

# 2. Ход работы

1. Делаем форк
   
2. Задаем имя аользователя и email
   
3. Клонируем удаленный репозиторий на компьютер
   
4. Добавляем файл через интерфейс github
   
5. Подтягиваем ищменения в локальный репозиторий
   
6. Получаем историю для каждой ветки
   
7. Смотрим последние изменения ветки
   
8. Выполняем слияние и разрешаем конфликт
   
9. Удаляем ветку master
   
10. Делаем изменение в mergefile.txt и коммитим
   
11. Создаем новый фвйл и коммитим
    
12. Делаем откат коммита
    
13. Создаем ветку для отчета и переходим в нее
    
14. Отправляем все в удаленный репозиторий


# 3. Лог команд

Ниже приведены команды, использованные в процессе работы:

git config global user.name/email
git clone https://github.com/zavraghost/LR6
git pull
git reflog --all
git log -p
git checkout branch1
git merge master
git diff
git add mergefile.txt
git status
git commit -m "merged"
git branch -d master
git add mergefile.txt
git commit -m "updated"
git add fileforcommit.txt
git commit -m "adding new file"
git reset --hard HEAD
git checkout -b report
git branch
git push --set-upstream origin report
