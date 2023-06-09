﻿Лабораторна робота №1 

Стадник Г.О. група; 536ст

Мета роботи: зарееструватися на Github та навчитися користуватися базовими командами у Git Bash 

Виконання завдання: 

1\. Спочатку створюємо аккаунт на Github:

![](Aspose.Words.fa2bca98-f633-40d9-b968-308c3324d1da.001.png)

Рисунок 1.1 — Профіль

2\. Далі я скачав звичайний додаток Git:

![](Aspose.Words.fa2bca98-f633-40d9-b968-308c3324d1da.002.png)

Рисунок 1.2 — Git Bash

3\. Для подальшої роботи налаштуємо гіт у Git Bash, від нас треба вказати ім’я аккаунта та пошту:

```
git config --global user.name "Hermann8086"
```

```
git config --global user.email h.o.stadnyk@student.khai.edu
```


4\. Геренуємо SSH ключ командою:

```
ssh-keygen -t ed25519 -C "h.o.stadnyk@student.khai.edu"
```

Отримали наш персональний файл з ключем

5\. Додаємо наш ключ до аккаунту Github у налаштуваннях:

![](Aspose.Words.fa2bca98-f633-40d9-b968-308c3324d1da.003.png)

Рисунок 1.3 — SSH ключ

6\. Створюємо наш репозиторій та налаштовуємо його:

![](Aspose.Words.fa2bca98-f633-40d9-b968-308c3324d1da.004.png)

Рисунок 1.4 — Створення репозиторію

![](Aspose.Words.fa2bca98-f633-40d9-b968-308c3324d1da.005.png)

Рисунок 1.5 — Сам репозиторій

7\. Завантажимо репозиторій по ssh ключу, спочатку копіюємо ключ у репозиторії, а потім у консоль пишемо команду:

![](Aspose.Words.fa2bca98-f633-40d9-b968-308c3324d1da.006.png)

Рисунок 1.6 — SSH ключ репозиторія

```
git clone git@github.com:Hermann8086/LAB1-2.git
```

![](Aspose.Words.fa2bca98-f633-40d9-b968-308c3324d1da.007.png)

Рисунок 1.7 — Папка репозиторія

8\. Всі команди та послідовність як зробити комміт наших файлів у папку репозиторію:

```
cd шлях до файлу
```

```
git clone  посилання(ключ HTTPS або SSH) до репозиторію
```

```
cd назва нашого репозиторію
```

```
git status
```

```
git add .
```

```
git status
```

```
git commit -m "Будь-який коментарій"
```

```
git push
```

```
git status
```

Висновки:

В лабораторній роботі 1 було ознайомлення з функціоналом, налаштуванням та командами які є у GitHub.

Також створено GitHub аккаунт, згенерован SSH ключ, створили репозиторій, завантажили на PC та внесли зміни, зробивши нову версію завантажили на свій GitHub аккаунт. Завантажувати звичайні файли у репозиторій можна, але можна завантажити і вірус таким чином, тому у репозиторій завантажують файли з розширенням(.md), що означає Markdown, такі файли безпечніші та виглядають красиво і практично, що можна побачити у цій лабораторній роботі. Також людям простіше сприймати інформацію, і файл(.md) перший файл який бачить людина або ще хтось.

