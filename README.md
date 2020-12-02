





# 0.学习笔记

### 1.JavaScript笔记

1.1js中document.write()会向body中写入内容

1.2.js文件引用

```html
<script type='text/javascript' src= 'js/script.js'></script>
```

1.3.js注释

```j s
单行注释    ／／

多行注释   ／*      多行内容           *／
```

```
javascript:$(".share-method-line").parent().append('<div class="share-method-line"><input type="radio"id="share-method-public"name="share-method"value="public"checked=""><span class="icon radio-icon icon-radio-non"></span><label for="share-method-public"><b>公开分享</b></label></div>')
```



### 2.python基础笔记

### 3.jquery笔记

[3.1.jquery-W3school](https://www.w3school.com.cn/jquery/index.asp)

3.2.常用事件函数

![image-20200420204228761](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200420204228761.png)

3.3页面加载完毕执行js代码 

![image-20200421160348201](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421160348201.png)

3.4用$符号书写

![image-20200421160657874](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421160657874.png)

3.5jquery对象和dom对象

![image-20200421160926723](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421160926723.png)

![image-20200421161129855](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421161129855.png)

3.6jquery对象和dom对象转换

jQuery没有play方法，只能使用Dom对象

谷歌浏览器会禁用视频播放，处理办法：加一个muted

![image-20200421161507641](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421161507641.png)

两者转换：

![image-20200421161603031](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421161603031.png)

![image-20200421161648160](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421161648160.png)

3.7jQuery选择器

![image-20200421162016998](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421162016998.png)

jQuery层级选择器

![image-20200421162200649](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421162200649.png)

3.8jQuery设置样式不能使用原生js的style

![image-20200421162417822](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421162417822.png)

```js
$('ul li:first').css('color','red')
```

![image-20200421162650503](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421162650503.png)

even 偶数  odd奇数

3.9jQuery筛选择器

![image-20200421162755769](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421162755769.png)

3.10jQuery筛选方法

![image-20200421163200685](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421163200685.png)

![image-20200421163528677](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421163528677.png)

tab栏切换

![image-20200421163807502](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421163807502.png)

查找兄弟元素使用siblings()

![image-20200421164042830](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421164042830.png)

nextAll()是之后的所有元素   prevtAll()是之前的所有元素

![image-20200421164213914](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421164213914.png)

查找第n个元素和判断是否含有某个类名

![image-20200421164544555](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421164544555.png)

3.11jQuery中的拍他思想

![image-20200421164831140](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421164831140.png)

3.12淘宝tab栏案例

![image-20200421165306972](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421165306972.png)

![image-20200421165422931](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421165422931.png)

![image-20200421165526706](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421165526706.png)



3.13



```js
  <script>
        $(function() {
            $("a").click(function(event) {
                event.preventDefault();
                // var id = $(this).attr('href').split('?')[1].split('&')[0].split('=')[1];
                var id = $(this).attr('href')[1]
                console.log(id);
            });
        })
    </script>
```

3.14







### 4.前端学习笔记

4.1 p标签是块级元素，自动换行，input标签是内连元素，不会自动换行

```HTML
4.2 <p></p>标签是段落标签
<br/>换行标签 
```

4.3文本格式化标签

![image-20200421135600142](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421135600142.png)

![image-20200421143030699](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200421143030699.png)

4.4

### 5.echarts笔记

### 6.爬虫笔记

### 7.semantic笔记

### 8.小程序笔记

# 1.python自动化

# 2.python基础

#  3.python数据分析

#  4.python爬虫

#  5.python GUI

#  6.python网站

#  7.echarts

## [7.1echarts数据可视化项目](https://www.bilibili.com/video/BV1v7411R7mp/?spm_id_from=333.788.videocard.0)

#  8.python 数据库

#  9.前端

## [9.1黑马程序员前端入门](https://www.bilibili.com/video/BV14J4114768)

![image-20200417232021518](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200417232021518.png)

## [9.2js部分pink老师](https://www.bilibili.com/video/BV1M7411T7u2/?spm_id_from=333.788.videocard.0)  

![image-20200418201939092](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418201939092.png)

![image-20200418202053706](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418202053706.png)

![image-20200418204101223](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418204101223.png)

 ![image-20200418204320295](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418204320295.png)

![image-20200418204818917](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418204818917.png)

![image-20200418210053647](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418210053647.png)

![image-20200418211035533](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418211035533.png)

  ![image-20200418230133236](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418230133236.png)

![image-20200418230722347](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200418230722347.png)





## [9.3 JavaScript webapi+jquery+js高级](https://www.bilibili.com/video/BV167411p7hi?from=search&seid=3003814238568012274)  

## [9.4 移动web开发之流式布局](https://www.bilibili.com/video/BV1m7411s7WY/?spm_id_from=333.788.videocard.2)

## [9.5 移动web开发之flex布局](https://www.bilibili.com/video/BV1BJ41197XE/?spm_id_from=333.788.videocard.2)  

## [9.6 移动WEB开发（rem）布局](https://www.bilibili.com/video/BV1m7411s7TY/?spm_id_from=333.788.videocard.14)  

## [9.7 移动开发之响应式布局](https://www.bilibili.com/video/BV1AJ411i7HF?from=search&seid=11446121305653412879)  

## [9.8 黑马Pink老师教你学前端之基础篇之一](https://www.bilibili.com/video/BV187411y73j)

## **[9.9 黑马Pink老师教你学前端之基础篇之二](https://www.bilibili.com/video/BV1d7411X7nd)**  

## [9.10最新版JavaScript全套基础课程](https://www.bilibili.com/video/av95136001/?spm_id_from=333.788.b_636f6d6d656e74.4)

## [9.11jquery全套实战教程](https://www.bilibili.com/video/BV1zE411K7Ji/?p=2)

## [9.12精通网页布局](https://www.bilibili.com/video/BV1aJ411i7jz)

## [9.13前端基础](https://www.bilibili.com/video/BV1iE411y7hb?from=search&seid=6893815587856882716)

## [9.14javascript基础](https://www.bilibili.com/video/BV1YW411T7GX/?spm_id_from=333.788.videocard.7)

##  [9.15jquery-W3school](https://www.w3school.com.cn/jquery/index.asp)

## [9.16jquery2020实战教程](https://www.bilibili.com/video/BV17K411L7vz?)

#  10.响应式网页开发

## [10.1 bootstrap中文网站](https://www.bootcss.com/)  

##  [10.2移动WEB开发-Bootstrap案例](https://www.bilibili.com/video/BV1R7411s72K?)

###  10.2.1开发原理

###  ![image-20200417215219064](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200417215219064.png) 10.2.2尺寸划分

![image-20200417215632603](/Users/xushuaikui/Library/Application Support/typora-user-images/image-20200417215632603.png)



##  [10.3semantic ui文档](https://zijieke.com/semantic-ui/introduction/getting-started.php)

## [10.4 semantic ui文档视频](https://zijieke.com/d/86)

## [10.5JavaScript交互式网站实战开发](https://www.bilibili.com/video/BV1p4411Q7pT/?spm_id_from=333.788.videocard.4)

10.5.1 异步：一次干多件事    同步：一次干一件事

10.5.2









#  11.微信小程序

## [11.1微信小程序从入门到实战](https://www.bilibili.com/video/BV1WJ41197sD?)  

完整接口文档 请看这里 https://www.showdoc.cc/128719739414963?page_id=2612830563673346

素材以及教案下载地址： https://gitee.com/xiaoqiang001/small_program.git