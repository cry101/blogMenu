# blogMenu
自动生成博客目录

<h4>you should:</h4>
<div class="highlight highlight-text-html-basic">
<pre>
&lt;<span class="pl-ent">link</span> <span class="pl-e">rel</span>=<span class="pl-s"><span class="pl-pds">"</span>stylesheet<span class="pl-pds">"</span></span> <span class="pl-e">type</span>=<span class="pl-s"><span class="pl-pds">"</span>text/css<span class="pl-pds">"</span></span> <span class="pl-e">href</span>=<span class="pl-s"><span class="pl-pds">"</span>css/jquery.autoMenu.css<span class="pl-pds">"</span></span>&gt;
</pre>
</div>
or youself css;

<h4>you need put jquery before my plugin</h4>
<div class="highlight highlight-text-html-basic">
<pre>
&lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>https://code.jquery.com/jquery-3.2.1.min.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;
&lt;<span class="pl-ent">script</span> <span class="pl-e">src</span>=<span class="pl-s"><span class="pl-pds">"</span>js/jquery.autoMenu.js<span class="pl-pds">"</span></span>&gt;&lt;/<span class="pl-ent">script</span>&gt;
</pre>
</div>

<h4>how to use：</h4>
<div class="highlight highlight-text-html-basic">
<pre>
you can just:
<div class="autoMenu" id="autoMenu" data-autoMenu></div>
or:
$("#autoMenu").autoMenu({
    levelOne : 'h3', //一级标题
    levelTwo : 'h4',  //二级标题（暂不支持更多级）
    width : 200, //容器宽度
    height : 400, //容器高度
    padding: 20, //内部间距
    offTop : 100 //滚动切换导航时离顶部的距离
});
</pre>
</div>
<h4>or see in [demo](https://cry101.github.io/2017/03/03/ES6-01/) :)</h4>
