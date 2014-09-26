Jeet Snippets
=============

Sublime Text snippets for the [Jeet grid system](http://jeet.gs)


Installation
------------

#### Using [Package Control](https://sublime.wbond.net):

* Open the Command Palette
* Package Control: Install Package
* Search for Jeet Snippets
* Install


Usage
-----

Type a **Trigger** below and press `tab`. The snippet will be inserted with the `highlighted` text highlighted.

These triggers work anywhere in a `.styl` or `.scss` file.

| Trigger | Stylus                  | SCSS                           |
| ------- | ----------------------- | -----------------------------  |
| alb     | align(`both`)           | @include align(`both`);        |
| alh     | align(`horizontal`)     | @include align(`horizontal`);  |
| alv     | align(`vertical`)       | @include align(`vertical`);    |
| cen     | center()                | @include center();             |
| cf      | cf()                    | @include cf();                 |
| col     | column(1/`3`)           | @include column(1/`3`);        |
| cg      | column-gutter(1/`3`)    | @include column-gutter(1/`3`); |
| cw      | column-width(1/`3`)     | @include column-width(1/`3`);  |
| edit    | edit(`black`)           | @include edit(`black`);        |
| sh      | shift(1/`3`)            | @include shift(1/`3`);         |
| span    | span(1/`3`)             | @include span(1/`3`);          |
| stack   | stack()                 | @include stack();              |
| uns     | unshift()               | @include unshift();            |
| unstack | unstack()               | @include unstack();            |

These triggers work only as arguments inside the functions/mixins above.

| Trigger | Stylus                  | SCSS                          |
| ------- | ----------------------- | ----------------------------- |
| align   | align: `center`         | $align: `center`              |
| cs      | col\_or\_span: `column` | $col\_or\_span: `column`      |
| cyc     | cycle: `3`              | $cycle: `3`                   |
| gut     | gutter: `3`             | $gutter: `3`                  |
| mw      | max\_width: `100`px     | $max\_width: `100`px          |
| off     | offset: 1/`3`           | $offset: 1/`3`                |
| pad     | pad: `100`px            | $pad: `100`px                 |
| unc     | uncycle: `3`            | $uncycle: `3`                 |
