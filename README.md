# jQuery-Inline-Popup

A jQuery Plugin to show content within inline.

InlinePopup is a simplified jquery plugin to achieve expanding preview as like Google Image.

Here the steps to configure...

**Step 1 :** Download and link to the Jquery plugin

**Step 2 :** Download and link to the Jquery inlinePopup plugin

**Step 3 :** Fire the jQuery inlinePopup Plugin 
```javascript
$(document).ready(function(){
	$("#wrapper-container").inlinePopup({itemSelector : ".items"})
});
```

## Plugin Options

*  **itemSelector**
*  **ipclass**
*  **ipcloseclass**
*  **iparrowclass**
*  **ipcontentwrapperclass**
*  **descriptionElem**
*  **activeFirst**
*  **scrollToViewPort**
*  **arrow**
*  **scrollOffset**
*  **closeinnerelem**

## Getting started

### HTML

Include the inlinePopup .js file in your site.
```
<script src="/path/jquery-inline-popup.min.js"></script>
```

InlinePopup works on a container element with a group of similar child items.

```
<div id="wrapper-container">
  <div class="items">...</div>
  <div class="items">...</div>
  <div class="items">...</div>
  <div class="items">...</div>
  ...
</div>
```

### CSS

All sizing of items is handled by your CSS.

```
#wrapper-container { position:relative; }
.items { width:250px; height:250px; float:left; }
.ip-details { display:none; }
```

### Initialize with jQuery
```
$("#ip-container").inlinePopup({
	itemSelector : ".article",
	closeinnerelem:"X"
})
```



