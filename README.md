![pickList is a simple plugin for jQuery.](http://s9.postimg.org/li46m3gvj/pick_List.png)

<h2>
<a name="installation" class="anchor" href="#installation"><span class="mini-icon mini-icon-link"></span></a>Installation</h2>

<p>Include script <em>after</em> the jQuery library:</p>

<pre><code>&lt;script src="pickList.js"&gt;&lt;/script&gt;
</code></pre>


<h2>
<a name="usage" class="anchor" href="#usage"><span class="mini-icon mini-icon-link"></span></a>Usage</h2>

<p>Basic setup:</p>

```html
<div id="pickList"></div>  <!-- HTML -->
```

```javascript
$("#pickList").pickList(); // JS
```
<p>To set data into the plugin just include:</p>
```javascript
var valSelected = {
  01: {id: 16,text: 'Alex'},
  02: {id: 17,text: 'Rose'},
  03: {id: 18,text: 'Lily'},
  04: {id: 19,text: 'Ha'}};
var val = {
    01: {id: 01, text: 'Isis'},
    02: {id: 02, text: 'Sophia'},
    03: {id: 03, text: 'Alice'},
    04: {id: 04, text: 'Isabella'},
    05: {id: 05, text: 'Manuela'},
    06: {id: 06, text: 'Laura'}
  };

var pick = $('#pickList').pickList({
                data: values,
                dataSelected: values1
            });
```
<p>To get data just call the getValues:</p>
```javascript

 $("#getSelected").click(function () {
     console.log(pick.getValues());
 });
```
<h2>
<a name="demo" class="anchor" href="#demo"><span class="mini-icon mini-icon-link"></span></a>Demo</h2>
<p><strong><a href="https://jsfiddle.net/Alexrgs/f5vuczb2/">pickList Jsfiddle Show + Code</a></strong> </p>
<p><strong><a href="https://jsfiddle.net/Alexrgs/f5vuczb2/show/">pickList Jsfiddle Show</a></strong> </p>
<h2>
<a name="authors" class="anchor" href="#authors"><span class="mini-icon mini-icon-link"></span></a>Author</h2>

<p><a href="http://pt.stackoverflow.com/users/17658/gabriel-rodrigues" target="_blank">Gabriel Rodrigues</a></p>

