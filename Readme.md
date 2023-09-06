## Header
*чтобы текущая страница в шапке была выделена как на макете*
нужно добавить к .menu__item класс **_active**
>menu-item _active>

>menu-right__item _active>

В верстке на примере страницы руководства

## Минимизирования
я использую сборку **webpack+gulp** для минимизирования стилей и скриптов

чтобы активный элемент подсвечивался необходимо вместо *content-menu-closed* добавить класс **content-menu-active**
>content-menu__item content-menu-active>

**.content-menu-active** также открывает последующий уровень меню также стрелка переворачивается.

если активный пункт внутри подменю то активный пункт меню получает класс **content-menu-active**
>content-menu__item content-menu-active>

а для раскрытия верхних уровней к верхнему элементу меню добавляется класс **content-menu-open**
>content-menu__item content-menu-open>

> 1. content-menu__item content-menu-closed

    1.1 content-menu__item content-menu-closed

        1.1.1 content-menu__item

    1.2 Раздел АБ

делаем вот так

> 1. content-menu__item content-menu-open

    1.1 content-menu__item content-menu-open

        1.1.1 content-menu__item content-menu-active

    1.2 Раздел АБ

