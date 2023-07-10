
Nastya 
1. Клонировала репозиторий: git clone git@github.com:elizabethsal/QAmobile.git 
2. перешла в ветку course: git checkout course
3. Создала файлы с текстом внутри: 
     cat >>about_nastya.json
     cat >>about_job_nastya.txt
4. залила на git через fork
5. Отредактировала файл about_nastya.json:  nano about_me.json 
   После редактирования Ctrl+О, далее Enter. Для выхода Ctrl+x
   Отредактировала файл about_job_nastya.txt:  vi about_job.txt  
   Для начала редактирования текста нажать i, для сохранения Esc, :wq
6. залила изменения через fork
7. создала файл:  touch readme.txt
8. проверка изменений: git fetch
9. залила readme.txt: git commit -a 
 git push origin course
