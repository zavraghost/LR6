# LR6
Лабораторная работа №6
# Отчёт по выполнению лабораторной работы

# 1. Цель работы

Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт 
работы с локальным и удаленным репозиторием.

# 2. Ход работы

1. Делаем форк
   ![1](https://github.com/zavraghost/LR6/blob/report/images/11.png)
2. Задаем имя аользователя и email
   ![2](https://github.com/zavraghost/LR6/blob/report/images/1.png)
3. Клонируем удаленный репозиторий на компьютер
   ![3](https://github.com/zavraghost/LR6/blob/report/images/3.png)
4. Добавляем файл через интерфейс github
   ![4](https://github.com/zavraghost/LR6/blob/report/images/4.png)
5. Подтягиваем ищменения в локальный репозиторий
   ![5](https://github.com/zavraghost/LR6/blob/report/images/5.png)
6. Получаем историю для каждой ветки
   ![6](https://github.com/zavraghost/LR6/blob/report/images/6.png)
7. Смотрим последние изменения ветки
   ![7](https://github.com/zavraghost/LR6/blob/report/images/7.png)
8. Выполняем слияние и разрешаем конфликт
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

# 4. История операций

commit 26c0adc61c4ae9afac94ff6964787d3125ee2c6e (HEAD -> report, origin/report, branch1) </br>
Author: 4319NikolaevaVI <zavraghost@gmail.com> </br>
Date:   Fri Nov 15 05:17:24 2024 +0300 </br>

    adding new file

commit bfc27139a0f875fb0979cfc71ed91033079684a4 </br>
Author: 4319NikolaevaVI <zavraghost@gmail.com> </br>
Date:   Fri Nov 15 05:16:08 2024 +0300 </br>

    updated

commit dccdf6bc54ac8d2c465e9b0c1f7fc86ca768cdf6 </br>
Merge: 67b2c7c 0f9f50d </br>
Author: 4319NikolaevaVI <zavraghost@gmail.com> </br>
Date:   Fri Nov 15 05:14:26 2024 +0300 </br>

    merged

commit 67b2c7c55a83932d5e4ade1277bdadf2cedcc5cf (origin/master, origin/HEAD) </br>
Author: Viktoriia Nikolaeva <144121477+zavraghost@users.noreply.github.com> </br>
Date:   Fri Nov 15 04:14:02 2024 +0300 </br>

    Create NewFile

commit 921f53b8d0cebf542c791cf31f04e9b792f385a4 </br>
Author: Kurtyanik <45309985+Kurtyanik@users.noreply.github.com> </br>
Date:   Sat Nov 21 20:09:49 2020 +0300 </br>

    Обновление информации
