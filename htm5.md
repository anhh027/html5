html5 新增结构性标签
 
section 区块 章节
1.把页面划分n多块
2.article > section
article可以和section相互嵌套
<article>
 <h3>热卖手机</h3>
 <section> 
 <h4>华为</h4>
 <p></p>
 <p></p>
 </section>
 </article>

 hgrounp
 <hgroup>
 	<h1>主标题</h1>
 	<h3>副标题</h3>
 </hgroup>

<section>
	<h2>娱乐</h2>
</section>
<section>
	<h2>军事</h2>
</section>

header 可以代表页面头部、区块头部、文章头部
footer 可以代表页面底部、区块底部、文章底部

<header>
	logo、网站标题、
	导航
	<nav>
		<ul>
			<li>首页</li>
			<li>首页</li>
			<li>首页</li>
			<li>首页</li>
			<li>首页</li>
			<li>首页</li>
		</ul>
	</nav>
</header>
<footer>
	底部导航、友情链接、版权
</footer>


figure 默认带有margin和padding  对图片进行修饰的

pre和code结合使用 可以在页面中显示代码
<pre>
	<code>
		.box{
		width:300px;
		height:300px;
		}
	</code>
</pre>

<dialog>hello!</dialog>   只有谷歌可以用

meter的默认值是0-10
写上min和max的话值时介于俩者之间
<meter min=0 max=100 value=50></meter>
<time>让浏览器知道该内容表示的是时间</time>
<progress></progress>表示的是进度条

javascript
1.效果   属性、内容、样式
2.操作数据  ajax+js

输入时会有一些推荐内容提示
<input type="text" list="txt">
<datalist id="txt">
	<option value="香蕉"></option>
	<option value="苹果"></option>
	<option value="梨"></option>
	<option value="橘子"></option>
</datalist>