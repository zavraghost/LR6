# LR6
Лабораторная работа №6
# Отчёт по выполнению лабораторной работы

# 1. Цель работы

Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт 
работы с локальным и удаленным репозиторием.

# 2. Ход работы

1. Делаем форк
   ![1](https://github.com/zavraghost/LR6/blob/report/images/11.png)
2. Задаем имя пользователя и email
   ![2](https://github.com/zavraghost/LR6/blob/report/images/1.png)
3. Клонируем удаленный репозиторий на компьютер
   ![3](https://github.com/zavraghost/LR6/blob/report/images/3.png)
4. Добавляем файл через интерфейс github
   ![4](https://github.com/zavraghost/LR6/blob/report/images/4.png)
5. Подтягиваем изменения в локальный репозиторий
   ![5](https://github.com/zavraghost/LR6/blob/report/images/5.png)
6. Получаем историю для каждой ветки
   ![6](https://github.com/zavraghost/LR6/blob/report/images/6.png)
7. Смотрим последние изменения ветки
   ![7](https://github.com/zavraghost/LR6/blob/report/images/7.png)
8. Выполняем слияние и разрешаем конфликт </br>
   8.1. Переходим в ветку branch1
      ![81](https://github.com/zavraghost/LR6/blob/report/images/81.png)
   8.2. Выполняем слияние и получаем ошибку
      ![82](https://github.com/zavraghost/LR6/blob/report/images/82.png)
   8.3. Смотрим в чем причина ошибки
      ![83](https://github.com/zavraghost/LR6/blob/report/images/83.png)
   8.4. Исправляем файл
   
      ![84](https://github.com/zavraghost/LR6/blob/report/images/84.png)
   
   8.5. Добавляем содержимое рабочего каталога в индекс для последующего коммита, проверяем была ли исправлена ошибка и делаем коммит.
      ![85](https://github.com/zavraghost/LR6/blob/report/images/85.png)
10. Удаляем ветку master
   ![9](https://github.com/zavraghost/LR6/blob/report/images/9.png)
11. Делаем изменение в mergefile.txt и коммитим
   ![10](https://github.com/zavraghost/LR6/blob/report/images/10.png)
12. Создаем новый фвйл и коммитим
    ![11](https://github.com/zavraghost/LR6/blob/report/images/111.png)
13. Делаем откат коммита
    ![12](https://github.com/zavraghost/LR6/blob/report/images/12.png)
14. Создаем ветку для отчета и переходим в нее
    ![13](https://github.com/zavraghost/LR6/blob/report/images/13.png)
15. Отправляем все в удаленный репозиторий
    ![14](https://github.com/zavraghost/LR6/blob/report/images/14.png)

# 3. Лог команд

Ниже приведены команды, использованные в процессе работы:

git config global user.name/email </br>
git clone https://github.com/zavraghost/LR6 </br>
git pull </br>
git reflog --all </br>
git log -p </br>
git checkout branch1 </br>
git merge master </br>
git diff </br>
git add mergefile.txt </br>
git status </br>
git commit -m "merged" </br>
git branch -d master </br>
git add mergefile.txt </br>
git commit -m "updated" </br>
git add fileforcommit.txt </br>
git commit -m "adding new file" </br>
git reset --hard HEAD </br>
git checkout -b report </br>
git branch </br>
git push --set-upstream origin report </br>
git log --pretty=format:"%h %ad %an %s" --graph --date=short </br>

# 4. История операций в форматированном виде
![15](https://github.com/zavraghost/LR6/blob/report/images/15.png)
