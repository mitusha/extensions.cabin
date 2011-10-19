#mquery.cabin.css
This extensions adds a width based media query to your project which will scale the <code>body</code>, <code>.wrapper</code>, <code>ul, ol</code> according to the width of the screen viewing it. You can add in your own width-based changes too.

##How to include this extension

There are 2 ways to include this extension .css file in your project:

<pre><code>@charset "UTF-8";
@import url("mquery.cabin.css");
/*==================================================*/
/*  Cabin CSS Framework 1.0.4 by Adam Whitcroft     */
/*  hello[at]adamwhitcroft[dot]com                  */
/*  @adamwhitcroft                                  */
/*==================================================*/
</code></pre>

Or, you can add a <code>&lt;link /&gt;</code> inside the <code>&lt;head&gt;</code> of your page <strong>after</strong> the core <code>cabin.css</code> link.

<pre><code>&lt;!DOCTYPE html&gt;
&lt;head&gt;
  &lt;title&gt;Let's hug kittens!&lt;title&gt;
  &lt;!-- Core Cabin .css file --&gt;
  &lt;link rel="stylesheet" href="cabin.css" /&gt;
  &lt;!-- Cabin extension .css file --&gt;
  &lt;link rel="stylesheet" href="mquery.cabin.css" /&gt;
&lt;/head&gt;
</code></pre>