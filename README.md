# Ранее просмотренные товары

> Для работы нужен localforage (//cdnjs.cloudflare.com/ajax/libs/localforage/1.5.0/localforage.min.js)

```twig
Чтобы запомнить товар, добавьте на страницу данный дата атрибут, в значение указать product.id
<div data-recently-view="{{ product.id }}"></div>
```
> Вызовите `new RecentlyView` на страницах товара и страницах где нужно вывести список товаров.
> В колбек `success` выводится массив с json просмотренных товаров. Для отрисовки используйте js шаблонизаторы.

```js
var myRecentlyView = new RecentlyView({
 success: function (_products) {
   console.log(_products);
 }
});
```
