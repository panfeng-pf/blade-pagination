blade-pagination
==============
Pagination, a jQuery plugin.<br/>
Demo is in package.

Demo Snapshot
--------------
![github](https://raw.githubusercontent.com/panfeng-pf/blade-pagination/master/snapshot/examples.png "blade-pagination")

Dependency
--------------
* jQuery

How to Use
--------------
### Import CSS
```html
<link rel="stylesheet" type="text/css" href="blade-pagination.css" >
```

### Import JS
```html
<script src="jquery.min.js"></script>
<script src="jquery.blade-pagination.js"></script>
```

### Initial pagination
```html
<script type="text/javascript">
  $(function() {
	$('selector').bladePagination();
	// or $('selector').bladePagination(options);
  });
</script>
```

### Option Description
```javascript
{
    maxPageNum: 5,
    firstLabel: '|&lt;', // |<
    prevLabel: '&lt;',   // <
    nextLabel: '&gt;',   // >
    lastLabel: '&gt;|',  // >|
    moreLabel: '...',
    rebuildAfterClick: false,
    clickPage: function(page) {}
}
```
