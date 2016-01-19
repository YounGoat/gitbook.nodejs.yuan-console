# Advanced UI: Checkbox Group

```javascript
var options = [ 'one', 'two', 'three'];

var cg = new yuancon.UI.CheckboxGroup({
	title  : 'CHECKBOX TITLE',
	options: options
});

cg.on('check', function(option, index) {
	// ...
});

cg.on('uncheck', function(option, index) {
	// ...
});

cg.on('close', function(options, checked) {
	// ...
});

cg.display();
```
