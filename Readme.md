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

чтобы открывался список и работала стрелка добавляем **content-menu-open**
>content-menu__item content-menu-open>
