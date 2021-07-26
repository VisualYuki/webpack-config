- [Редактирование Readme.md (Frontend, Backend)](#редактирование-readmemd-frontend-backend)
- [Для BACKEND разработчика](#для-backend-разработчика)
	- [from Backend for FrontEnd (Нужно заполнить)](#from-backend-for-frontend-нужно-заполнить)
	- [Frontend for Backend (Нужно сделать)](#frontend-for-backend-нужно-сделать)
- [Для FRONTEND разработчика](#для-frontend-разработчика)
	- [FrontEnd начало работы](#frontend-начало-работы)
	- [CSS сокращения](#css-сокращения)
	- [Webpack tasks](#webpack-tasks)
		- [Production mode](#production-mode)
		- [Development mode](#development-mode)
	- [Библиотеки ( в процессе редоктирования)](#библиотеки--в-процессе-редоктирования)
	- [Cтруктура проекта ( в процессе редактирования)](#cтруктура-проекта--в-процессе-редактирования)
	- [Особенности сайта](#особенности-сайта)
	- [Обратная связь с Fronend разработчиком](#обратная-связь-с-fronend-разработчиком)

# Редактирование Readme.md (Frontend, Backend)

-  Убедительная просьба следить за структурой и чистотой написанного вами текста.
-  Использовать markdown preview для отслеживания корректности вашего текста

# Для BACKEND разработчика

## from Backend for FrontEnd (Нужно заполнить)

-  Есть ли локально сервер и где он лежит. Какой домен сайта в интернете на период натяжки и боегого развертывания.
   > Тут пишется ответ
-  Есть ли деплой, и как он работает.
   > Тут пишется ответ
-  Как проходит процесс от коммита изменений до появления изменений на сайте (домене, локальном сервере), т.е. что я должен сделать, чтобы правки были на сайте.
   > Тут пишется ответ
-  Структура папок и особенно где лежит весь html код сайта Т.е. для каждой страницы указать где лежит весь html, который используется на этой странице.
   > Пр. <br>
   > Основной шаблон - frontend\views\layouts\main.php и подключаемые файлы в frontend\views\layouts\main\
   > Части страниц - frontend\views\parts\
   > Главная страница - frontend\views\site\index.php и подключаемые файлы в frontend\views\site\index\
-  Где подгружаеются скипты, стили в php
   > Тут пишется ответ
-  Информацию для обратной связи.
   > Тут пишется ответ
-  Что должен знать Frontend разработчик со стороны Backend'a, чтобы начать делать свою работу. (Пр. Если я запушу изменения на гит, правки появяться на сайте? Что иначе нужно делать? )
   > Тут пишется ответ

## Frontend for Backend (Нужно сделать)

-  Файлы с исходниками обязательно должны лежать, либо на локальном сервере, либо на хостинге. т.е. вся ветка front должна быть неделима. т.к. брать только выходную папку (frontend-dist) не нужно, так как правки вносяться через исходники (src)
-  Убедительная просьба. Если идет только натяжка, то если что-то непонятно, то лучше написать мне и обсудить это, либо найти компромис вместе, так как в будущем не хочется разбираться почему верстка работает не так, как должна.<br>
   Обратная связь: vk - https://vk.com/moshkin_denis, или telegram - @denis_moshkin
-  Когда вы перености мою верстку из ветки front в master, то папку frontend-src коммитить не нужно, так как потом все изменения в гите будут показывать на вас. P.S. после натяжки я в любом случае буду делать правки и закомичу свои файлы.

# Для FRONTEND разработчика

## FrontEnd начало работы

-
-
-

## CSS сокращения

-  l (local) - локальные стили для блока выше
-  b (bem) - бэм блок, которые повторяется больше одного раза
-  d (display) - блок для мониторов
-  m (mobile) - блок для мобилок
-  t (tablet) - блок для планшета

## Webpack tasks

### Production mode

-  `npm run prod:build` - компиляция всего проекта, с удалением выходной папки + запуск сервера.

### Development mode

-  `npm run dev:serve` - запуск сервера (без минификации и т.д.)/
-  `npm run dev:build` - компиляция всего проекта, с удалением выходной папки + запуск сервера

## Библиотеки ( в процессе редоктирования)

-  Модальные окна - fancybox (http://fancyapps.com/fancybox/3/docs)
-  Слайдер - slick-slider (https://kenwheeler.github.io/slick/)
-  Шаблон ввода в input - jQuery Masked Input Plugin (https://github.com/digitalBush/jquery.maskedinput)
-  Выпадающий список - select2 (https://github.com/select2/select2)
-  Ленивая загрузки изображений - lazysizes (https://github.com/aFarkas/lazysizes)
-  Кастомный скролл - simplebar (https://github.com/Grsmto/simplebar)
-  Таймер - easytimer.js (https://github.com/albert-gonzalez/easytimer.js)
-  Выпадающий список - select2 (https://github.com/select2/select2)
-

## Cтруктура проекта ( в процессе редактирования)

-  dist - папка с выходными файлами, формируется только gulp'ом

-  src - папка с исходниками

## Особенности сайта

1.
2.

## Обратная связь с Fronend разработчиком

vk: https://vk.com/moshkin_denis <br>
telegram: @denis_moshkin
