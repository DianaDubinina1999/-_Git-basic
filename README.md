Для выполнения задания необходимо:
1. Клонировать на свой локальный компьютер пустой репозиторий

2. Добавить в свой локальный репозиторий (прямо в master) файл Potter.txt, содержащий список книг (именно в том виде, как оно приведено справа).
После добавить(push) файл Potter.txt в свой удалённый репозиторий на GitHub
Harry Potter book
One The Philosopher's Stone (1997)
two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
4etyre The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

3. Создать ветку feature, изменить в ней содержание файла Potter.txt на новое содержание (справа).
После этого закоммитить (commit) изменения в ветку feature.
Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
chetyre The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

4. Через master, изменить содержание файла Potter.txt на ещё один вариант (справа).
После закоммитить (commit) изменения в ветку master и
сделать push в удалённый репозиторий.
Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

5. Снова перейти в ветку feature и вмерджить в неё master

6. Разрешить мердж-конфликт таким образом, чтобы в ветке feature
появился правильный вариант Potter.txt.
После этого закоммитить (commit) изменения ветки feature
Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

7. Изменить файл в ветке feature добавив в него «:» в конце самой 1-ой строки
После этого закоммитить (commit) изменения ветки feature
Harry Potter book:
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

8. Через master изменить содержание файла Potter.txt на ещё один вариант.
После этого закоммитить (commit) изменения ветки master
Harry Potter book
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
tri The Prisoner of Azkaban (1999)
4 The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)

9. Вмерджить feature в master и обновить Potter.txt, разрешить конфликт в ветке master так, чтобы в результате получился правильный вариант текста:
Залить(push) изменения ветки master в удалённый репозиторий
Harry Potter book:
One The Philosopher's Stone (1997)
Two The Chamber of Secrets (1998)
Three The Prisoner of Azkaban (1999)
Four The Goblet of Fire (2000)
Five Order of the Phoenix (2003)
Six Half-Blood Prince (2005)
Seven Deathly Hallows (2007)
