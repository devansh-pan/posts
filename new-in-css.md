---
title: New in CSS
description: CSS new features you need to know
date : 08-01-2025
reading: 2 MIN
author: krishna Gita
tags : [css, web ]
---
<div class="p-3 m-0 bg-red-200">
<h1> 🎉 What is new in CSS </h1>
<br/>
<small> Author: *Krishna Gita* &nbsp; Updated on: 08-01-2025  &nbsp; Reading time: 2 min </small>
 </div>
 
 ---
 
CSS added new features last year. Most of them are supported by all major browsers and baseline available.

[Visit chrome.dev for full details](https://chrome.dev/css-wrapped-2024/)

Below are what I thought usefull for UI developer.
## 1.Field-sizing
  > This setting allows `inputs, textarea, select` elements to grow with content within them as user types or selects.The element's size gets adapted to the content they have.
```css
textarea, select, input {
  field-sizing: content;
}
```
## 2. Stylable `details` tag
 > The `details` tag now can be styled. `::details-content` pseudo-element can be used to style `details` tag. 
 ```css
 details {
  display: flex;
  flex-direction: row;
}
```
## 3. `scrollbar-color` and `scrollbar-width`
> We can now style scrollbar color and width.
```css
.scroller {
  scrollbar-color: hotpink blue;
  scrollbar-width: 10%;
}
```
## 4. Popover API
> You can now create popovers ,menus, info boxes without Javascript or z-index headache with just CSS.Just add id of popover element to popovertarget property of button and see the majic without javascript.
```html
<button popovertarget="my-popover">Open Popover</button>
<div id="my-popover" popover>
  <p><p>I am a popover with more information. Hit <kbd>esc</kbd> or click away to close me.<p></p>
</div>
```
That's for now. Have a good day 

