<?php
// Сообщение
$message = "Line 1\name\nLine 2\email\nLine 3\message";

// На случай если какая-то строка письма длиннее 70 символов мы используем wordwrap()
$message = wordwrap($message, 70, "\r\n");

// Отправляем
mail('r.i.d.i.k.7@mail.ru', 'My Subject', $message);
?>
