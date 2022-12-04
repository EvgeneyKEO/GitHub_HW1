### _CONTENT_ 
__________________________________________________________________________________
### [:arrow_forward: JSON](https://github.com/EvgeneyKEO/GitHub_HW1#large_orange_diamond-json)
### [:arrow_forward: XML](https://github.com/EvgeneyKEO/GitHub_HW1#large_orange_diamond-xml)
### [:arrow_forward: TXT](https://github.com/EvgeneyKEO/GitHub_HW1#large_orange_diamond-txt)
__________________________________________________________________________________

### **_GitHub. HW_1_**
> Созданные файлы по домайшней работе находятся в отдельных репозиториях ([JSON](https://github.com/EvgeneyKEO/JSON.git), [XML](https://github.com/EvgeneyKEO/XML.git), [TXT](https://github.com/EvgeneyKEO/TXT.git))
 1. Создайте текстовый файл как в первом ДЗ по Terminal
 2. Сценарий перенесите в этот файл.
 3. На против каждого действия - напишите команду в GitBash
 _________________________________________________________________________________
### :large_orange_diamond: JSON
 _________________________________________________________________________________
 1. Создать внешний репозиторий c названием JSON            - [JSON](https://github.com/EvgeneyKEO/JSON.git)

 2. Клонировать репозиторий JSON на локальный компьютер
```
git clone git@github.com:EvgeneyKEO/JSON.git
```
 3. Внутри локального JSON создать файл “new.json”
``` 
touch new.json
```
 4. Добавить файл под гит.
```
git add .
```
 5. Закоммитить файл.
```
git commit -m "add new file"
```
 6. Отправить файл на внешний GitHub репозиторий.
 ```
git push
```
 7. Отредактировать содержание файла “new.json” - написать 
информацию о себе (ФИО, возраст, количество домашних
животных, будущая желаемая зарплата). Всё написать в формате JSON.                                
```
vim new.json ---> input data ---> esc ---> enter ":wq"
```                                                            
 8. Отправить изменения на внешний репозиторий.  [new.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/new.json)
 ```
 git commit -am "update file" && git push
 ```
 9. Создать файл preferences.json 
```
touch preferences.json
```
 10. В файл preferences.json добавить информацию о своих 
предпочтениях (Любимый фильм, любимый сериал, любимая еда,
любимое время года, сторона которую хотели бы посетить) в формате JSON.
```
vim preferences.json ---> input data ---> esc ---> enter ":wq"`
```
 11. Создать файл skills.json добавить информацию о скиллах
которые будут изучены на курсе в формате JSON               
```
cat >> skills.json ---> input data ---> ctrl + c
```
 12. Отправить сразу 2 файла на внешний репозиторий. [preferences.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/bug_report.json)   [skills.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/skills.json)
 ```
 git add . && git commit -m "add new file" && git push
 ```
 13. На веб интерфейсе создать файл bug_report.json.        
```
Add file --> Create new file --> Name: bug_report.json
```
 14. Сделать Commit changes (сохранить) 
изменения на веб интерфейсе.				    - `Commit new file`  [bug_report.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/skills.json)

 15. На веб интерфейсе модифицировать файл 
bug_report.json, добавить баг репорт в формате JSON.        - `Choose bug_report.json --> Edit this file` 

 16. Сделать Commit changes (сохранить) изменения
на веб интерфейсе.					    - `Commit changes`

 17. Синхронизировать внешний и локальный репозиторий JSON
```
git pull
```
_________________________________________________________________________________
### :large_orange_diamond: XML
 _________________________________________________________________________________
 1. Создать внешний репозиторий c названием XML.            - [XML](https://github.com/EvgeneyKEO/XML.git)
 2. Клонировать репозиторий XML на локальный компьютер.     
```
git clone https://github.com/EvgeneyKEO/XML.git
```
 3. Внутри локального XML создать файл “new.xml”.           
 ```
 touch new.xml
```
 4. Добавить файл под гит.                                  
```
git add .
```
 5. Закоммитить файл.                                      
``` 
git commit -m "add new file"
```
 6. Отправить файл на внешний GitHub репозиторий.         
```
git push
```
 7. Отредактировать содержание файла “new.xml” - написать 
информацию о себе (ФИО, возраст, количество
домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
vim new.xml ---> input data ---> esc ---> enter ":wq"
```
 8. Отправить изменения на внешний репозиторий. [new.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/new.xml)
``` 
git commit -am "update file" && git push
``` 
 9. Создать файл preferences.xml 
```
touch preferences.xml
```
 10. В файл preferences.xml добавить информацию о своих 
предпочтениях (Любимый фильм, любимый сериал, любимая еда,
любимое время года, сторона которую хотели бы посетить) в формате XML. 
```
vim preferences.xml ---> input data ---> esc ---> enter ":wq"
```
 11. Создать файл skills.xml добавить информацию о скиллах
 которые будут изучены на курсе в формате XML		     
```
cat >> skills.xml ---> input data ---> ctrl + c`
```
 12. Сделать коммит в одну строку. 
```
git add . && git commit -m "Add new files"
```
 13. Отправить сразу 2 файла на внешний репозиторий. [preferences.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/preferences.xml) [skills.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/skills.xml) 
```
git push
```
 14. На веб интерфейсе создать файл bug_report.xml. [bug_report.xml](https://github.com/EvgeneyKEO/XML/blob/80e38f039f2898659ea6d7ffd6e2477226ddcb08/bug_report.xml)
```
Add file --> Create new file --> Name: bug_report.xml
``` 
 15. Сделать Commit changes (сохранить) изменения 
на веб интерфейсе.					      
```
Commit new file
```
 16. На веб интерфейсе модифицировать файл bug_report.xml, 
добавить баг репорт в формате XML. 		     	      
```
Choose bug_report.xml --> Edit this file
``` 
 17. Сделать Commit changes (сохранить) 
изменения на веб интерфейсе.			      	      
```
Commit changes
```
 18. Синхронизировать внешний и локальный репозиторий XML.    
```
git pull
```
 _________________________________________________________________________________
### :large_orange_diamond: TXT
 _________________________________________________________________________________

 1. Создать внешний репозиторий c названием TXT.	      - [TXT](https://github.com/EvgeneyKEO/TXT.git)
 2. Клонировать репозиторий TXT на локальный компьютер	      
```
git clone https://github.com/EvgeneyKEO/TXT.git
```
 3. Внутри локального TXT создать файл “new.txt”.	    
 ```
 touch new.txt
 ```
 4. Добавить файл под гит.				    
 ```
 git add .
 ```
 5. Закоммитить файл.					      
```
git commit -m "add new file"
```
 6. Отправить файл на внешний GitHub репозиторий.	     
```
git push
```
 7. Отредактировать содержание файла “new.txt” - написать    
 информацию о себе (ФИО, возраст, количество домашних 
 животных, будущая желаемая зарплата). Всё написать в формате TXT. 				      
```
vim new.txt ---> input data ---> esc ---> enter ":wq"
```
 8. Отправить изменения на внешний репозиторий.	    
```
git commit -am "update file" && git push
```
 9. Создать файл preferences.txt
```
touch preferences.txt
```
 10. В файл preferences.txt добавить информацию о своих 
 предпочтениях (Любимый фильм, любимый сериал, любимая еда, 
 любимое время года, сторона которую хотели бы посетить) 
 в формате TXT.						     
```
vim preferences.txt ---> input data ---> esc ---> enter ":wq"
```
 11. Создать файл skills.txt добавить информацию о скиллах 
 которые будут изучены на курсе в формате TXT.		      
```
cat >> skills.txt ---> input data ---> ctrl + c
```
 12. Сделать коммит в одну строку.			      
```
git add . && git commit -m "add new file"
```
 13. Отправить сразу 2 файла на внешний репозиторий. [preferences.txt](https://github.com/EvgeneyKEO/XML/blob/00af65bbb600b3df84979764c458fde3e9948652/preferences.xml) [skills.txt](https://github.com/EvgeneyKEO/XML/blob/00af65bbb600b3df84979764c458fde3e9948652/skills.xml)	      
```
git push
```								
 14. На веб интерфейсе создать файл bug_report.txt.	      
```
Add file --> Create new file --> Name: bug_report.txt
```
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. [bug_report.txt](https://github.com/EvgeneyKEO/XML/blob/00af65bbb600b3df84979764c458fde3e9948652/bug_report.xml)				      
```
Commit New File 
```
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.	
```
Choose bug_report.txt --> Edit this file
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
Commit changes
```
 18. Синхронизировать внешний и локальный репозиторий TXT     
```
git pull
```
