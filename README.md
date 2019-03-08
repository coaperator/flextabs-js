jQuery FlexTabs Plugin <sup>2.0.0</sup>
-------
_**jQuery-плагин**, для создания адаптивных вкладок (**табы**, **аккордеон**, **спойлер**)_

* Два режима отображения: tabs, accordion + (accordion с одной вкладкой в качестве спойлера)
* Адаптивный режим. Трансформация табов в аккордеон и обратно (произвольно или при заданной ширине окна браузера)
* Поддержка тем оформления (стили темы вынесены в отдельный файл)
* Гибкая система методов/событий для программного управления состояниями
* Пользовательская анимация при открытии/закрытии вкладок и смене режима
<br>

[Демо: Стандартный вариант](http://wahawaher.ru/flextabs-js/demo-default.html) | [Демо: Анимация](http://wahawaher.ru/flextabs-js/demo-animation.html) | [Документация](http://wahawaher.ru/flextabs-js)

## CDN:
```sh
// Последняя доступная версия
https://cdn.jsdelivr.net/gh/WahaWaher/flextabs-js/dist/jquery.flextabs.min.js
https://cdn.jsdelivr.net/gh/WahaWaher/flextabs-js/dist/jquery.flextabs.min.css
https://cdn.jsdelivr.net/gh/WahaWaher/flextabs-js/dist/jquery.flextabs.theme-default.min.css

// Версия на выбор
https://cdn.jsdelivr.net/gh/WahaWaher/flextabs-js@2.0.0/dist/jquery.flextabs.min.js
```

## Пакетные менеджеры:
```sh
# Bower
bower install --save flextabs-js

# NPM
npm install --save flextabs-js
```

## Подключение:

1. Подключить скрипты и стили:
```html
<!-- jQuery FlexTabs Styles -->
<link rel="stylesheet" href="dist/jquery.flextabs.min.css">

<!-- jQuery FlexTabs Theme Default -->
<link rel="stylesheet" href="dist/jquery.flextabs.theme-default.min.css">

<!-- jQuery -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<!-- jQuery FlexTabs -->
<script src="dist/jquery.flextabs.min.js"></script>
```
2. Инициализировать плагин на группе элементов:
```javascript
$('[data-ft]').flexTabs({
	// Параметры...
});
```
3. Применить в HTML:
```html
<div data-ft>
	<nav>
		<a href="#tab-1" class="active">Вкладка #1</a>
		<a href="#tab-2">Вкладка #2</a>
		<a href="#tab-3">Вкладка #3</a>
	</nav>
	<div>
		<div id="tab-1">Содержание вкладки #1</div>
		<div id="tab-2">Содержание вкладки #2</div>
		<div id="tab-3">Содержание вкладки #3</div>
	</div>
</div>
```
Другие варианты разметки см. [Документацию](http://wahawaher.ru/flextabs-js)

## Зависимости:
- [jQuery](http://jquery.com/download/) (тестировался на версии 3.3.1)

## Поддержка
Решение проблем/багов плагина, а также замечания и пожелания в [соответствующей теме](https://github.com/WahaWaher/flextabs-js/issues)

По всем другим вопросам:  [wahawaher@gmail.com](mailto:wahawaher@gmail.com "Написать на wahawaher@gmail.com")

## Лицензия (MIT)
Copyright (c) 2018-2019 Sergey Kravchenko

Данная лицензия разрешает лицам, получившим копию данного программного обеспечения и сопутствующей документации (в дальнейшем именуемыми «Программное Обеспечение»), безвозмездно использовать Программное Обеспечение без ограничений, включая неограниченное право на использование, копирование, изменение, слияние, публикацию, распространение, сублицензирование и/или продажу копий Программного Обеспечения, а также лицам, которым предоставляется данное Программное Обеспечение, при соблюдении следующих условий:

Указанное выше уведомление об авторском праве и данные условия должны быть включены во все копии или значимые части данного Программного Обеспечения.

ДАННОЕ ПРОГРАММНОЕ ОБЕСПЕЧЕНИЕ ПРЕДОСТАВЛЯЕТСЯ «КАК ЕСТЬ», БЕЗ КАКИХ-ЛИБО ГАРАНТИЙ, ЯВНО ВЫРАЖЕННЫХ ИЛИ ПОДРАЗУМЕВАЕМЫХ, ВКЛЮЧАЯ ГАРАНТИИ ТОВАРНОЙ ПРИГОДНОСТИ, СООТВЕТСТВИЯ ПО ЕГО КОНКРЕТНОМУ НАЗНАЧЕНИЮ И ОТСУТСТВИЯ НАРУШЕНИЙ, НО НЕ ОГРАНИЧИВАЯСЬ ИМИ. НИ В КАКОМ СЛУЧАЕ АВТОРЫ ИЛИ ПРАВООБЛАДАТЕЛИ НЕ НЕСУТ ОТВЕТСТВЕННОСТИ ПО КАКИМ-ЛИБО ИСКАМ, ЗА УЩЕРБ ИЛИ ПО ИНЫМ ТРЕБОВАНИЯМ, В ТОМ ЧИСЛЕ, ПРИ ДЕЙСТВИИ КОНТРАКТА, ДЕЛИКТЕ ИЛИ ИНОЙ СИТУАЦИИ, ВОЗНИКШИМ ИЗ-ЗА ИСПОЛЬЗОВАНИЯ ПРОГРАММНОГО ОБЕСПЕЧЕНИЯ ИЛИ ИНЫХ ДЕЙСТВИЙ С ПРОГРАММНЫМ ОБЕСПЕЧЕНИЕМ.