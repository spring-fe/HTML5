# HTML5
## 语义化
### strong
重要性、严重性和紧急性
### em
从一句话中突出某个词语
### b
将词语从视觉上和其他部分区分，比如一篇论文摘要中的关键词
### i
换一种语调去说一句话时，比如其他语言翻译，对话中的旁白
### dfn
定义
```html
<p>
  <dfn>
     HTML是HyperText Markup Language的简写，一种用户创建网页的标记语言。
  </dfn>
<p>
```
### abbr
缩写
```html
<p>
  <abbr title="HyperText Markup Language">HTML</abbr>标准由
  <abbr title="World Wide Web Consortium">W3C</abbr>制定和修改。
</p>
```
### code
```html
<p>
使用HTML5写页面,第一行要写<code>&lt;!DOCTYPE html&gt;</code>
</p>
```
### var
```html
<p>
能量<var>E</var>等于质量<var>m</var>乘以光速<var>c</var>的平方
</p>
```
### kbd
```html
<p>
按下<kbd>F12</kbd>打开浏览器开发者工具。
</p>
```
### samp
```html
<p>检查当前工作仓库状态:</p>
<pre><code>spring@localhost:camp$ <kbd>git status</kbd>
<samp>On branch master
Your branch is up-to-date with 'origin/master'.
</samp>
</code></pre>
```
### sup
上标
```html
<p>E = MC<sup>2</sup></p>
```
### sub
下标
```html
<p>CO<sub>2</sub></p>
```
### mark
和用户当前行为相关的突出，比如在搜索结果中匹配到的词；
一部分内容需要在后面引用时
### del
删除
```html
<p><del>原价:299元</del><ins>双11特价:188元</ins></p>
```
### ins
插入
```html
<p><del>原价:299元</del><ins>双11特价:188元</ins></p>
```
### br
换行
```html
<p>JavaScript<br>高级程序设计</p>
```
### wbr
```html
<p>https://zh.wikipedia.org/<wbr>wiki/<wbr>%E4%B8%87%E7%BB%B4<wbr>%E7%BD%91%E8%81%94%E7%9B%9F</p>
```
