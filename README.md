# LR6
# Лабораторная работа №6
## Система контроля версий 


Настроили клиент git, введя имя пользователя (Группа
Фамилия И.О.) и email. 
![](/screens/1.png)

Клонировали удалённый репозиторий на компьютер.
Добавили файл через интерфейс GitHub. Подтянули изменения в
локальный репозиторий. 
![](/screens/2.png)

Получили историю операций для каждой из веток. 
![](/screens/3.png)

Просмотрели последние изменения. 
![](/screens/4.png)

Выполнили слияние в ветку master, разрешив конфликт
![](/screens/5.png)

Удалили побочную ветку после успешного слияния
![](/screens/6.png)

Сделали изменения, зафиксировали их
![](/screens/7.png)

Сделали откат коммита и создали ветку для отчёта
![](/screens/8.png)


### Лог команд

<pre>
git config --global user.name 4215grebennikova_e_v
git config --global user.email egrebennikoff02@gmail.com
git clone https://github.com/ekaterin-grebennikoff2002/LR6.git
git pull
git log --all
git diff master~ master
git merge branch1
git push
git log
git push -d origin branch1
git branch
git commit -m "made change first time"
git commit -m "made change second time"
git log
git reset HEAD~1 --hard
git checkout -b otchyot
</pre>

### История операций в сокращенном виде 

<pre>git log --pretty=format:"%h - %ad | %an | %s" --date=short</pre>

![](/screens/9.png)