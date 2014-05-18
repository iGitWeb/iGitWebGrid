[iGitWebGrid](https://github.com/iGitWeb/iGitWebGrid) - A Simple Grid System in CSS
===================================================================================

iGitWebGrid is a simple an easy to use Grid System coded in CSS3 by Carlos Celma from [iGitWeb](http://web.igitsoft.com).

This Grid System is based in the [Bootstrap](http://getbootstrap.com/css/#grid) libriary.

Getting Started
-----------------------------------------------------------------------------------

<ol>
<li>Insert the iGitWebGrid Library in your html file<br>
<pre>
&lt;link href="css/iGitWebGrids.css" rel="stylesheet" type="text/css /&gt;
</pre>
</li>
<li>Lets Start to use the Grid System...</li>
</ol>

Implementation
------------------------------------------------------------------------------------

To implement the grid system you need to start with a row content that will align your columns from left to right <pre style="color:blue;">.row-lf</pre> or from right to left <pre style="color:orange;">.row-rg</pre>, then yo can use the columns as you need.

### Example

<pre>
&lt;div class="row-lf"&gt;
    &lt;div class="col-sm-9"&gt;.col-sm-9&lt;/div&gt;
    &lt;div class="col-sm-3"&gt;.col-sm-3&lt;/div&gt;
&lt;/div&gt;
</pre>

This will show 2 columns positioned from left to right, first with width-75% and second with width-25%.
As the Grid System is Responsive, when the screen is smaller than 768px, all the columns turn to width-100% and it looks in just a colum.

### Offsetting Columns

You can move your colums to the right or left depending of your row alignment just adding an offset class <pre style="color:blue;">.offset-sm-1</pre>.

### Example

<pre>
&lt;div class="row-rg"&gt;
    &lt;div class="col-sm-3"&gt;.col-sm-9&lt;/div&gt;
    &lt;div class="offset-sm-6 col-sm-3"&gt;.col-sm-3&lt;/div&gt;
&lt;/div&gt;
</pre>

This will show a column with width-25% at the right of the window, then a 6 columns space and then a column with width-25% at the left of the window.
