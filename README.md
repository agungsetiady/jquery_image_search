## Example

![alt text](https://github.com/agungsetiady/jquery_image_search/tree/master/img/demo.png?raw=true)

Example:
```js
<div class="containerItems">
   <div data-search="wordsearch1 wordsearch2">
   </div>
</div>
```

## How it Works?

1. Add jquery library and the e-search.js.
```js
<script src="js/jquery-3.1.0.min.js"></script>
<script src="e-search.js"></script>
```

2. Add containerItems class to the container of your items.
```js
<div class="row containerItems">
```

3. Add data-filter attribute to the items of your containerItems. Add your search words for each item. 
```js
<div data-search="western mahjong">
```

4. Add the selector of your input and Run the function of the e-search plugin.
```js
$('input.form-control.search-game').search();
```

## jQuery
jQuery Use the plugin as follows:
```javascript
   $('input').search();
```
When done searching and want to execute another code:
```javascript
   $('input').search(function(){ 			
      //execute after done typing.
   });
```