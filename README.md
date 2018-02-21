# Ранее просмотренные товары

> Для работы нужен localforage (//cdnjs.cloudflare.com/ajax/libs/localforage/1.5.0/localforage.min.js)

```twig
<div data-recently-view="{{ product.id }}"></div>
```

```js
var myRecentlyView = new RecentlyView({
 success: function (_products) {
   console.log(_products);
 }
});
```
