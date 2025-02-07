# Домашнее задание к занятию "`Git`" - `Смирнова Елена`


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

Что нужно сделать:

Зарегистрируйте аккаунт на GitHub.
Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».
Склонируйте репозиторий, используя https протокол git clone ....
Перейдите в каталог с клоном репозитория.
Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.
Выполните команду git status и запомните результат.
Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.
Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.
Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.
Ещё раз выполните команды git diff и git diff --staged.
Теперь можно сделать коммит git commit -m 'First commit'.
Сделайте git push origin master.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.


---

### Задание 2

Что нужно сделать:

Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
Добавьте файл .gitignore в следующий коммит git add....
Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
Сделайте коммит и пуш.
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.


---

### Задание 3

Что нужно сделать:

Создайте новую ветку dev и переключитесь на неё.
Создайте в ветке dev файл test.sh с произвольным содержимым.
Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.
Переключитесь на основную ветку.
Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.
Сделайте мердж dev ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
Сделайте пуш в основной ветке.
Не удаляйте ветку dev.
В качестве ответа прикрепите ссылку на граф коммитов https://github.com/ваш-логин/ваш-репозиторий/network в ваш md-файл с решением.

Ваш граф комитов должен выглядеть аналогично скриншоту:

[скрин для Git](https://private-user-images.githubusercontent.com/77622076/256180841-e73589cf-7e97-40e5-ac01-d1d55376f1b9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3Mzg4NDcyMDksIm5iZiI6MTczODg0NjkwOSwicGF0aCI6Ii83NzYyMjA3Ni8yNTYxODA4NDEtZTczNTg5Y2YtN2U5Ny00MGU1LWFjMDEtZDFkNTUzNzZmMWI5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTAyMDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwMjA2VDEzMDE0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTUwZDYwNDlmNDgzMWU4YTc0MmUyNDlhYzRhYTc5YTRlMWQwMjAxYmRjMTlmNGUyMDFmZDRkZDAyNjg5OTVlMGImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.sJRGYusi8giAr_DIt_ObiHEhd2MYLGBPxKAaXuwCVlo)


