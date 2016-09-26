Where is focus bookmarklet
==============================
2016-09-26



A bookmarklet that console.log the element which has focus.




How to use
---------------

### In Firefox

Paste the following code into a web page and open it in a browser,
then put add the link to your favorites (drag the link in your tool bar).


```html
<a href="<a href="javascript: console.log(document.activeElement);">Drag me in your favorites</a>
```



### In Chrome

In Chrome, click Bookmarks->Bookmark Manager.<br>
You should see a new tab with the bookmarks and folders listed.<br>
Select the "Bookmarks Tab" folder on the left.<br>
Click the "Organize" link, then "Add Page" in the drop down.<br>
You should see two input fields. ...<br>
Paste the javascript code below into the second field.<br>


```js
javascript: console.log(document.activeElement);
```





