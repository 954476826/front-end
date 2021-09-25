# 目录
  - [HTML](#HTML)
  - [CSS](#CSS)
  - [JavaScript](#JavaScript)
  - [VUE](#VUE)
  - [WebPack](#webPack)


### 学习网站和资料
   - [MDN Web Docs](https://developer.mozilla.org/zh-CN/docs/Web)
   - [浏览器开发者工具](https://developer.mozilla.org/zh-CN/docs/Learn/Common_questions/What_are_browser_developer_tools)
   - [readme语法1](https://github.com/guodongxiaren/README/blob/master/README.md#readme)
   - [readme语法2](https://github.com/kaivin/markdown/blob/master/readme.md)


### HTML
 1. 规范,语义化标签与分类
    >[HTML编码规范](https://github.com/ecomfe/spec/blob/master/html-style-guide.md#user-content-1-%E5%89%8D%E8%A8%80)  
  HTML是一门标记语言,它由一系列元素组成,这些元素可以用来展示不同的内容.   一个元素由开始标签,内容,结束标签组成  
  **块级元素和内联元素**  
  块级元素在页面中以块的形式展现,它通常独占一行,用来展示结构化的内容,例如段落,列表,导航,表单. 块级元素不会被嵌套进内联元素中，但可以嵌套在其它块级元素中  
  内联元素通常出现在块级元素中并环绕文档内容的一小部分,并不会导致换行
 2. 常用页面标签默认样式,属性
    * **语义标签**  
     >&lt; p &gt;段落  
     &lt; h1 &gt;标题,1~6表示不同级别  
     &lt; em &gt;:斜体  
     &lt; strong &gt;:粗体  
    * **List**  
     >无序列表[&lt; ul &gt;](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/ul)分组;  
     有序列表[&lt; ol &gt;](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/ol)分组;  
     [&lt; li &gt;](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/li)包裹单个项.
     
    * **超链接 [&lt; a &gt;](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/a)**
      * 可以将文档链接到任何资源，也可以链接到文档的指定部分  
      * URL、绝对路径和相对路径
      >绝对URL和相对URL  
你可能会在网络上遇到两个术语，绝对URL和相对URL（或者称为，绝对链接和相对链接）：  
绝对URL：指向由其在Web上的绝对位置定义的位置，包括 protocol（协议） 和 domain name（域名）。像下面的例子，如果index.html页面上传到projects这一个目录。并且projects目录位于web服务站点的根目录，web站点的域名为http://www.example.com，那么这个页面就可以通过http://www.example.com/projects/index.html访问（或者通过http://www.example.com/projects/来访问，因为在没有指定特定的URL的情况下，大多数web服务会默认访问加载index.html这类页面）
不管绝对URL在哪里使用，它总是指向确定的相同位置。  
相对URL：指向与您链接的文件相关的位置，更像我们在前面一节中所看到的位置。例如，如果我们想从示例文件链接http://www.example.com/projects/index.html转到相同目录下的一个PDF文件，URL就是文件名URL——例如project-brief.pdf——没有其他的信息要求。如果PDF文件能够在projects的子目录pdfs中访问到，相对路径就是pdfs/project-brief.pdf（对应的绝对URL是http://www.example.com/projects/pdfs/project-brief.pdf）

      * 在下载链接时使用 download 属性   
 3. 元信息类标签(head、title、meta)的使用目的和配置方法
    >头部元素  
    &lt; head &gt;元素,它的内容不会在浏览器中显示,它的作用是保存页面的一些元数据  
    &lt; title &gt;元素是一项元数据，用于表示整个HTML文档的标题  
    &lt; meta &gt;元素: 元数据,元数据就是描述数据的数据. [&lt; meta &gt;](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/meta)元素有很多种类  
    [&lt; link &gt;](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/link):外部资源链接元素,一般用来引入外部CSS文件或添加图标  
    &lt; script &gt;:引入或编写JavaScript代码  
    lang属性为文档设置主语言,这能被搜索引擎更有效地索引
 4. **[文档与网站架构](https://developer.mozilla.org/zh-CN/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)**
 4. **HTML5缓存**
 5. **即时通讯**
 6. **SVG**

### CSS
  1. 所有选择器优先级，权重，使用场景,继承
     >.class选择  
     #id选择  
     标签选择  
     结构选择  
     属性选择
     * 元素权重
     >元素会被多个样式一层层作用，这就是层叠样式表的来源。如果多个样式做用在元素上就会产生优先级权重问题。权重可以计算  
     
      | 选择器     | 权重 |
      | :---------:| :-------:|
      | 类.属性    | 0010 |
      | id        | 0100 |
      | 标签.伪元素| 0001 | 
      | 通配符     | 0000 |
      | 行内样式   | 1000 |
        
      
  3. 伪类和伪元素
     * **超链接伪类**  
      >:link有链接属性  
      :visited点击链接后  
      :hover鼠标悬停  
      :active点击未释放
     * :target:用于控制具有锚点目标元素的样式  
     * :root:根元素选择伪类即选择html  
     * :empty:没有内容和空白的元素
  5. 文本样式
  6. 盒模型,弹性盒模型
  7. 文档流,定位,浮动
  8. Bootstrap, 栅格布局
  9. 响应式布局,媒体查询
  10. 动画
  
### JavaScript
  1. 变量和类型
  2. 语法和API
  3. 函数和对象
  4. 作用域和闭包
  5. class
  6. 原型
  7. 正则表达式
  8. 模块化,导包
  9. 异步,Promise
  10. DOM和BOM,事件
  11. AJAX,json数据
  
### VUE

### WebPack

### HTTP 



