# LR_1

1. Що таке Git?
   Це система контроля версіями

2. В якому статусі можуть перебувати файли при роботі з Git?
   Змінений
   Індексований
   Збережений

3. Для чого використовується команда add?
   Щоб індексувати файл

4. Для чого використовується команда status?
   Переглянути поточний статус файлів

5. Для чого використовується команда commit?
   Перевести в збережений стан

6. Для чого використовується команда init?
   Ініціалізує репозиторій

7. Що необхідно писати в коментарях комітів?
   Описати все що ми зробили в цьому коміті

8. Як переглянути список комітів?
   git log

9. Для чого використовується команда checkout?
   Дозволяє переміщатись між гілками, відміняти зміни, створювати гілки



Лабораторна робота No3
Тема: Робота з командами Git, створення та злиття гілок

1. В якому статусі можуть перебувати файли при роботі з Git?
  збережений у коміті (commited)
  змінений (modified) 
  індексований (staged)

2. Для чого використовується команда add?
  Для індексації файла

3. Для чого використовується команда status?
  Переглянути поточний статус файлів

4. Для чого використовується команда commit?
  Перевести в збережений стан

5. Для чого використовується команда init?
  Ініціалізує репозиторій

6. Що необхідно писати в коментарях комітів?
  Описати все що ми зробили в цьому коміті

7. Для чого використовується команда checkout?
  Для переходу між гілками в репозиторії

8. Для чого використовується команда reset?
  Команда використовуеться для відміни локальних змін

9. Для чого використовується команда log?
  Щоб переглянути список комітів  

10.Для чого використовується команда status?
   Переглянути поточний статус файлів

11.Як відновити кілька файлів з попередньо створеного коміта? 
  git reset --hard COMMIT

12.Як перейди до попереднього коміта по імені?
git log, git checkout COMMIT_SHA

13.Як створити нову гілку?
  git branch назва-гілки

14.Як перейти на нову гілку?  
  git checkout назва-гілки

15.Як перейти на основну гілку?
  git checkout master

16.Як виконати злиття гілок?
  git checkout назва-гілки-1
  git merge назва-гілки-2