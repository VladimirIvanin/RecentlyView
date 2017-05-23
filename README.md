# Ранее просмотренные товары

> Работает только с common.js v2

```twig
<div data-recently-view="{{ product.id }}"></div>
```

```js
var myRecentlyView = new RecentlyView({
 succes: function (_products) {
   console.log(_products);
 }
});
```
