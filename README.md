# r_pageslider

A jQuery plugin to slide page

### Usage

#### HTML

```html
<div id="PAGE_WRAPPER" class="r_page_wrapper">
    <div class="r_page r_page_active" data-r_page_name="bgPage" style="background:#eee"></div>
    <div class="r_page" data-r_page_name="page1" style="background:blue"></div>
    <div class="r_page" data-r_page_name="page2" style="background:green"></div>
    <div class="r_page" data-r_page_name="page3" style="background:yellow"></div>
</div>
```

#### JAVASCRIPT

```javascript
$.r_pageslider.load('pageName') ;  //new page slide in from right side.
$.r_pageslider.loadFrom('pageName') ;  //old page slide out from left to right, new page reveals
```