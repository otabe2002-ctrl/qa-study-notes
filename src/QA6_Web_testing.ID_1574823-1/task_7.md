# Ссылка на сайт для проверки: https://korolev.hh.ru

**Общее количество ошибок:** 54 Errors, Warnings 8, info messages 24

**Количество критичных ошибок:**

Из критических можно отметить лишь Element [`img`](https://html.spec.whatwg.org/#the-img-element) is missing one or more of the following attributes: `src`, `srcset`.
Если у `<img>` нет `src` или `srcset`, браузер не знает, какую картинку показать.
Пользователь видит битую иконку или пустое место. Кол-во ошибок: 11

**Которые влияют на отображение или функциональность**: 2

* `Element img is missing one or more of the following attributes: src, srcset. (11)`
* `An img element must have an alt attribute`

**Самые частые типы ошибок:**

* **Element [`___`]() not allowed as child of element [`___`]() in this context. (Suppressing further errors from this subtree.) (**24)
  Элемент не может быть вложен в другой элемент в данном контексте — нарушены правила HTML, например, `<div>` внутри `<span>` или `<button>` внутри `<a>`.
* **The `___` attribute must not be specified on any `___` element unless the element has a `___` value other than `___`, `___`, `___`, `___`, `___`, `___`, `___`, `___`, `___`, `___`, or `___`. (14)**
  Атрибут `aria-label` нельзя использовать на элементе без явной семантической роли , иначе скринридеры не смогут корректно интерпретировать подпись.
* **Element [`img`](https://html.spec.whatwg.org/#the-img-element) is missing one or more of the following attributes: `src`, `srcset`. (11)**
  У тега `<img>` отсутствуют обязательные атрибуты `src` или `srcset` — браузер не знает, какую картинку загружать, и изображение не отобразится.

**Наличие ошибок доступности:**

* `An `img `element must have an`alt ` attribute, except under certain conditions`

Без `alt` сайт не соответствует стандартам доступности и исключает из пользовательского опыта людей с нарушениями зрения.

**Качество HTML-структуры:**  Большинство ошибок и предупреждений не критичины, требует мелких исправлений.

| Высокий                                                                                                                        | Средний                                                                                                                                                 | Низкий                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| Element[`img`](https://html.spec.whatwg.org/#the-img-element) is missing one or more of the following attributes: `src`, `srcset`. | Element[`___`]() not allowed as child of element [`___`]() in this context. (Suppressing further errors from this subtree.) Ошибка в синтаксисе | Attribute `xmlns:b` not allowed here.<br />ничего не ломает                               |
|                                                                                                                                       | `An img element must have an alt attribute Доступонось`                                                                                           | The `noindex` element is a completely-unknown element that is not allowed anywhere in any HTML content. |
