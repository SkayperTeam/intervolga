# intervolga
Тестовое задание для "ИНТЕРВОЛГА"  
**Файл shortened_link.php - выполнение 1-го задания:**  
 PHP и HTML. Напишите код на PHP  
В переменной $a лежит текст новости. В переменной $link лежит ссылка на страницу с полным текстом этой новости.
Нужно в переменную $b записать сокращенный текст новости по правилам:
- обрезать до 180 символов
- приписать многоточие
- последние 2 слова и многоточие сделать ссылкой на полный текст новости.  
Какие проблемы вы видите в решении этой задачи? Что может пойти не так?
Результат: ссылка на репозиторий с кодом и ваши комментарии.  
P.S. Проблем в решении не увидел. Всё пошло как надо.  
**Папка change_image - выполнение 2-го задания:**  
На диске лежит файл image.png, размер 20000 на 20000. Вывести картинку как баннер размером 200 на 100 пикселей.
Обратите внимание на размер и пропорции, и подумайте о времени загрузки.
Пришлите ссылку на репозиторий с решением
Важно: решение требует использования PHP, сжатие картинки средствами HTML/CSS является некорректным решением.  
P.S. index.php - вывод результата. image.php - обработка изображения  
**3-е задание:**  
Чем отличаются эти запросы:  
1. SELECT * FROM a, b WHERE a.id=b.a_id;  
2. SELECT * FROM a JOIN b ON a.id=b.a_id;  
Пришлите ответ текстом  
**ОТВЕТ:**  
Разница в том, что в первом варианте склеивание таблиц идёт через выборку таблицы a и b где id записи из таблицы "а" будет равен значению столбца a_id из таблицы "b"  
Во втором варианте идёт присоединение таблиц по id записи из "a" = значению столбца a_id из таблицы "b"  
P.S. Выполнение запроса выведет одинаковые результаты  
**Файл counting_identical_pairs.php - выполнение 4-го задания:**  
Дан массив из 100 элементов. Требуется вывести количество последовательных пар одинаковых элементов
Например: 1, 1, 2, 3, 4 -51, 12, 12, 12, -51
Пришлите ссылку на репозиторий с решением
