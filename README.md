# JSON
Task
Hello user!
I created a new repository with files that store information about me.
And here you can see what commands I used for this.
4. Создать внешний репозиторий c названием JSON: create a new repository
Создать ключ ssh : 
git config --global user.email "valerylanchinskaya@gmail.com"
git config --global user.name "valeriia888"
Valery@DESKTOP-EEF72K9 MINGW64 /g/work/GIT_Home_work_1 (main)
git config --global user.email
valerylanchinskaya@gmail.com
git config --global user.name
valeriia888
ssh-keygen -t rsa -C "valeriia888"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/andre/.ssh/id_rsa):
/c/Users/andre/.ssh/id_rsa already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/andre/.ssh/id_rsa
Your public key has been saved in /c/Users/andre/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:a+1Yv862qCyS8wv2R9Y4PXWKpD2VCugGk1blGNrd7Wc valeriia888
The key's randomart image is:
+---[RSA 3072]----+
|      ...        |
|     o.= . .     |
|    .oo.o . ..   |
|    = . . ..+ .  |
|   . +  SO =.oE  |
|      o *oO .o   |
|    oo oo.oo     |
|   .+o.o.+ +.    |
|     ++++.oo*o   |
+----[SHA256]-----+

 5. Клонировать репозиторий JSON на локальный компьютер: $ git clone git@github.com:valeriia888/JSON.git
 6. Внутри локального JSON создать файл “new.json”: touch new.json
 7. Добавить файл под гит:  git add .
 8. Закоммитить файл :  git commit -m "add json file"
 9. Отправить файл на внешний GitHub репозиторий. git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 cat >> new.json
11. Отправить изменения на внешний репозиторий. 
git add . && git commit -m "added  information abour me" && git push
 12. Создать файл preferences.json  touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 cat >> preferences.json
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  touch sklls.json && cat >> preferences.json
 15. Отправить сразу 2 файла на внешний репозиторий.
git add preferences.json  sklls.json $$ git commit -m "added  information about my preferences and skils " && git push
 16. На веб интерфейсе создать файл bug_report.json. add file button
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. commite new file 
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. edit file
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе. commite new file
 20. Синхронизировать внешний и локальный репозиторий JSON git pull
