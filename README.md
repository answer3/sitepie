Описание скрипта генератора статических сайтов

1. Необходимо создать новую папку с названием сайта в папке 
input(например, input/test/). имя должно быть без пробелов. 
Скопировать в папку csv файл и шаблоны index.html, post.html 
и tag.html

2. Запуск из командной строки - php run.php <имя_папки>
(например, php run.php test)

3. Выходные файлы будут записаны в папку html_output/<имя_папки>
(например, html_output/test)

4. Страницы постов сохраняются с именем post-<title_поста_в_csv>.html

5. Логи сохраняются в папке log