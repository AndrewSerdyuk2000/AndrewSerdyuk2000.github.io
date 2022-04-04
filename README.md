<html lang="ru">
<head>
<meta charset="utf-8" />
<title>SUITE</title>
</head>
<body>
  
<!--Создаём таблицу контейнер, которой задаём следующее
оформление:
border="1" - рамка вокруг контейнера. Увеличив число, можно увеличить толщину рамки.
align="center" - размещаем контейнер по центру экрана.
rules="rows" - убираем двойную рамку.
style="width:60%;" - добавляем стилевое свойства, делающее
контейнер и весь сайт "резиновым"-->
  
<table
border="1"
width="100%"
rules="rows">
<tr>
  <tr>
  
<!--TEXT-->
<!--В ячейке строки создаём ещё одну таблицу для шапки сайта.
Оформление:
border="1" - двойная рамка толщиной в 1px
background="images/168.png" - картинка в шапке сайта, если требуется.
Адрес картинки вы должны вставить свой.
bgcolor="#7FFFD4" - фоновый цвет в шапке, если нет картинки.
cellpadding="10" - отступ содержимого от рамки не менее 10px.
style="width:100%; border-radius:5px;" - добавляем "резиновость"
и закругляем уголки рамки-->
  
<table
width="100%"
border="1"
background="https://"
bgcolor="#7FFFD4"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку таблицы-->
<tr>

<!--Создаём столбец таблицы-->
<!--Содержание ячейки столбца-->
<h1>Типо сайт (халям балям (с) Beatles)</h1>
<h3>Что-то типо блога</h3>
<!--Закрываем таблицу-->

</tr>
  
 <!--</table>-->

<!--ОСНОВНОЙ КОНТЕНТ-->

<!--В этой же ячейке контейнера создаём ещё одну таблицу
для основного контента.
Оформление как и в предыдущей таблице-->

<table
background="https://sun9-39.userapi.com/impf/Z26gVF1WdfgzvYCff-tIkQMIrsWnuTGOpTDPtg/i1mAf6tudeA.jpg?size=810x1080&quality=95&sign=2592a4d65c89c648399d49ac490ba96a&type=album"
border="1"
bgcolor="#e6e6fa"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку-->
<tr>
  
<!--Создаём ячейку
Оформление:
rowspan="2" - объединяем две ячейки в одну.
Число объединяемых ячеек по числу ячеек в сайдбаре.
style="width:80%" - основной контент занимает 80% всей площади,
оставшиеся 20% для сайдбара-->
  
<td
rowspan="2"
style="width:80%">
<h2>PagePage</h2>
<!--Начинаем абзац с красной строки-->
<p style="text-indent:20px">
Personal blog. At work for N term..</p>

<p style="text-indent:20px">Text.</p>
<!--Закрываем ячейку-->
</td>

<!--САЙДБАР-->

<!--Создаём ячейку сайдбара-->
<td bgcolor="#e6e6fa">
<h3>Menu</h3>
<!--Абзац для ссылки на страницу сайта-->
<p>
<!--Ссылка на страницу сайта-->
<a href="https://vk.com/vkandreyt">
<!--Картинка маркера перед названием страницы-->
<img src="https://img.icons8.com/clouds/2x/vk-com.png">
<!--Название страницы
style="margin-left:5px;" - отступ названия от маркера-->
<span style="margin-left:10px;">VK</span></a>
<!--Закрываем абзац-->
</p>
  
<p>
<a href="https://vk.com/vkandreyt">
<img src="https://img.icons8.com/clouds/2x/vk-com.png">
<span style="margin-left:5px;">Page 1</span></a>
</p>
  
<p>
<a href="https://vk.com/vkandreyt">
<img src="https://img.icons8.com/clouds/2x/vk-com.png">
<span style="margin-left:5px;">Page 2</span></a>
</p>
<!--Закрываем строку Меню-->
 <!-- 
</td>
</tr>
  -->
<!--Создаём строку с дополнительной информацией-->
<tr>
<!--Ячейка с дополнительной информацией-->
<td
bgcolor="#73738c"
align="center">
<h3>Info stend</h3>
<p>There is information above</p>
<!--Закрываем ячейку с общей информацией
и таблицу основного контента-->
</td>
</tr> 

<!--Создаём таблицу подвала-->
<table
border="1"
bgcolor="#7FFFD4"
height="100"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку.-->
<tr>
<!--Создаём столбец-->
 
<h3>DOWN</h3>
<!--Закрываем таблицу подвала. При желании в подвале можно
сделать несколько строк и столбцов-->
  <p>Создано при поддержки себя</p>
</tr>


  <!-- </table>
Закрываем таблицу контейнера
</td>
</tr>
</table>
</body>
</html>
-->
