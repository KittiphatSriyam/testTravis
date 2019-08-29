---
title: How to use display property in css ?
date: "2019-09-29T22:14:20.284Z"
description: "the display property specifies the display behavior (the type of rendering box) of an element. In HTML, the default display property value is taken from the HTML specifications or from the browser/user default style sheet."
---

<h2>display: In-line</h2>
<p>เป็น property ที่จะไม่ขึ้นบรรทัดใหม่ </p>
<code>
&#x3C;style&#x3E;<br />
    &emsp;.redBox { <br />
        &emsp;&emsp;display: inline;<br />
        &emsp;&emsp;padding: 20px;<br />
        &emsp;&emsp;margin-left: 30px;<br />
        &emsp;&emsp;border: 1px solid blue;<br />
        &emsp;&emsp;background-color: rgb(255, 36, 36);<br />
    &emsp;}<br />
    &emsp;.buleBox { <br />
        &emsp;&emsp;display: inline;<br />
        &emsp;&emsp;padding: 20px;<br />
        &emsp;&emsp;border: 1px solid blue;<br />
        &emsp;&emsp;background-color: rgb(36, 229, 255);<br />
    &emsp;}<br />
&#x3C;/style&#x3E;<br />
</code>
<code>
    &#x3C;a href="google"&#x3E;Google&#x3C;/a&#x3E; <= คลิก <br />
    &#x3C;span&#x3E;Google Span Tag&#x3C;/span&#x3E; <= inline<br />
    --------------------------------------------------<br />
    &#x3C;div class="buleBox"&#x3E;&#x3C;/div&#x3E;
    &#x3C;div class="redBox"&#x3E;&#x3C;/div&#x3E;
</code>
    <br />
    <a href="google">Google</a> <= คลิก
    <br />
    <span>Google Span Tag</span> <= inline
    <br />
    <br />
    <br />
    <div>
        <div class="buleBox"></div>
        <div class="redBox"></div>
    </div>
    <br />
    <hr />
<h2>display: Inline-block</h2>
<p> จะเหมือนกับ Inline แต่จะสามารถ set ความสูง , ความกว้าง , (margin/padding) top bottom ได้ </p>
<code>
&#x3C;style&#x3E;<br />
    &emsp;span.b { <br />
        &emsp;&emsp;display: inline-block;<br />
        &emsp;&emsp;width: 100px;<br />
        &emsp;&emsp;height: 100px;<br />
        &emsp;&emsp;padding: 5px;<br />
        &emsp;&emsp;border: 1px solid blue;<br />
        &emsp;&emsp;background-color: rgb(36, 229, 255);;<br />
    &emsp;}<br />
&#x3C;/style&#x3E;<br />
</code>
<code>
   <br />
    &#x3C;div&#x3E;<br />
        &emsp;Lorem ipsum dolor sit amet<br />  
        &emsp;&emsp;&#x3C;span&#x3E;  class="b"&#x3E;Aliquam&#x3C;/span&#x3E; <br />
        &emsp;&emsp;&#x3C;span&#x3E;  class="b"&#x3E;venenatis&#x3C;/span&#x3E;  <br />
        &emsp; gravida nisl sit amet <br />
    &#x3C;/div&#x3E;
</code>
<div>Lorem ipsum dolor sit amet <span class="b">Aliquam</span> <span class="b">venenatis</span> gravida nisl sit amet  </div>
    <br />
    <hr />

<h2>display: block</h2>
<p>การแสดงผลบนหน้าเว็บบราวเซอร์แบบ Block คือข้อความในแท็กนั้นจะขึ้นบรรทัดใหม่ทันที</p>

<code>
&#x3C;style&#x3E;<br />
    &emsp;span.c { <br />
        &emsp;&emsp;display: block;<br />
        &emsp;&emsp;width: 100px;<br />
        &emsp;&emsp;height: 100px;<br />
        &emsp;&emsp;padding: 5px;<br />
        &emsp;&emsp;border: 1px solid blue;<br />
        &emsp;&emsp;background-color: rgb(36, 229, 255);<br />
    &emsp;}<br />
&#x3C;/style&#x3E;<br />
</code>
<code>
   <br />
    &#x3C;div&#x3E;<br />
        &emsp;Lorem ipsum dolor sit amet<br />  
        &emsp;&emsp;&#x3C;span&#x3E;  class="c"&#x3E;Aliquam&#x3C;/span&#x3E; <br />
        &emsp;&emsp;&#x3C;span&#x3E;  class="c"&#x3E;Aliquam&#x3C;/span&#x3E;  <br />
        &emsp;gravida nisl sit amet facilisis. Nullam cursus fermentum  velit sed laoreet.  <br />
    &#x3C;/div&#x3E;
</code>

<div>Lorem ipsum dolor sit amet <span class="c">Aliquam</span> <span class="c">venenatis</span> gravida nisl sit amet facilisis. Nullam cursus fermentum velit sed laoreet. </div>
<hr />
<h2>display: None</h2> 
<p>	เป็นการปิดการแสดงของ element</p>

<code>
    &#x3C;span style="display:none;"&#x3E;One Block&#x3C;/span&#x3E;
</code>
