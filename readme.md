# color-picker

A color-picker custom element for Polymer 1.0.
See it in action at https://freehand.firebaseapp.com/ 

Color-picker fires a "pick" event whenever the selected color changes.

```html
<color-picker on-pick="colorChange"></color-picker>
```
```javascript
colorChange: function(e) {
    var color=e.detail.color; //returns a string 'rgba(x,y,z,a)'
}
```