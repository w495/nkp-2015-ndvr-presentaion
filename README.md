== Что это ==

* ...

== Требования ==

* `make`;
* `XeLaTeX`;
* `beamer` (библиотека для `*TeX`);
* `tikz` (библиотека для `*TeX`);
* `polyglossia` (библиотека для `XeLaTeX`);
* ...

Если чего-то будет не хватать, то не трудно поставить
по мере надобности, или отключить в стилях (`./styles`).

=== Шрифты ===

* `SansRoundedLightC`
* `SansRoundedC`
* `Textbook New`

Используемые шрифты не прилагаются.

== Установка ==

=== Глобальная ===

Для сборки установите тему `tvzavr` для `beamer`.
Она описана в `./styles/Pres/`. У меня темы ставятся в

    /usr/share/texlive/texmf-dist/tex/latex/beamer/themes/theme/

=== Локальная ===

    make localthemes

== Сборка ==

    make all

== Структура ==

    .
    |-- src/    # исходные коды презентации.
    |-- img/    # изображения.
    `-- styles/ # стили.
