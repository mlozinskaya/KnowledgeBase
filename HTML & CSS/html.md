# Основы HTML (кратко)

### Теги

По типу делятся на:
* Семантические - понятно определяемые элементы (заголовки, абзацы, шапка...)
* Несемантические - неопределенные (span и div)

<br>

По расположению делятся на:
* Блочные - встравиаются со следующей строки (div, p...)
* Строчные - встраиваются как часть строки (span, button...)


// вставить картинку //

---

### Атрибуты тегов
---
#### Button

    <Button disabled type="..."> ... </Button>

disabled - логический атрибут <br>
type - тип кнопки 

Типы кнопок:

* button
* submit  
* reset 

submit, rest - для форм
<br>

---

#### img

    <img src="img/example.png">

// вставить картинку //

---

#### link

    <link rel="..." href="...">

rel - тип внешнего файла (стиль, иконка...) <br>
href - путь

---

#### a
    <a href="..." target="_blank">...</a>
target="_blank" - открыть ссылку в новой вкладке

---

#### form

    <form action="..." method="..."> </form>

action - адрес, куда будут отправлены данные <br>
method - метод отправки (GET, POST)

---

#### input

    <input type="...">

Типы полей ввода:
* text
* email
* password
* number
* tel

<br>

Многострочный текст:

    <textarea> ... </textarea>

Текстовая метка:

    <label for="name"> ... </label>
    <input id="name" type="text"> 

связывается с полем ввода атрибутом for (вводится id элемента)

---

### select

    <select>
        <option>Январь</option>
        <option>Февраль</option>
        ...
    </select>

Выбор нескольких вариантов:

    <select multiple> ... </select>