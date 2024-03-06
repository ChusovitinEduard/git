# Домашнее задание к занятию "`Git`" - `Чусовитин Э.А.`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

1. `Аккаунт на GitHub зарегистрирован`  
2. `Публичный репозиторий создан` 
   * Галочка в поле «Initialize this repository with a README» проставлена. 
 
 ![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/1.PNG)
 
3. * Выполняю git clone

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/2.PNG)

4. `Перехожу в каталог с клоном репозитория.`

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/3.PNG)

5. `Произвожу первоначальную настройку Git` 

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/4.PNG)

6. `Выполняю команду git status и запомниаю результат` 

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/5.PNG)

7. `Редактирую файл README.md при помощи nano, файл в состоянии Modified.`
 
![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/6.PNG)

8. `Перевожу файл в состояние staged, добавляю файл в коммит, командой git add README.md.` 

9. `Сделаю коммит git commit -m 'test commit'.` 

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/7.PNG)

13. `Делаю git push origin .` 

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/8.PNG)

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/9.PNG)

![ссылка на коммит test commit](https://github.com/ChusovitinEduard/git/commit/39b2756c7f919ce518aaf89cbedbb0971ce21fb9)

---

### Задание 2

1. `Создаю файл .gitignore, проверяю его статус сразу после создания.`

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/2_1.PNG)

2. `Добавляю файл .gitignore в коммит git add .gitignore` 

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/2_2.PNG)

3. `Добавляю правила в файл .gitignore, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.`
4. `Делаю комит и пуш` 

![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/2_3.PNG)
  

![ссылка на коммит Second Commit](https://github.com/ChusovitinEduard/git/commit/d9100f7f75e91b6cf91529e7b185e54cd65216c1)

### Задание 3

1. `Создаю новую ветку dev и сразу переключаюсь на неё. git checkout -b dev` 
2. `Создаю файл test.sh с произвольным содержимым.` 
3. `Сделаю несколько коммитов и пушей, имитируя активную работу над файлом test.sh.` 
4. `Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать git merge.`
5. `Сделайте коммит и пуш.` 
![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/3_1.PNG)
![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/3_2.PNG)
![alt text](https://github.com/ChusovitinEduard/git/blob/main/img/3_3.PNG)

![ссылка на граф коммитов](https://github.com/ChusovitinEduard/git/tree/dev?tab=readme-ov-file)
