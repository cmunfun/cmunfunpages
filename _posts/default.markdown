# 一、新文章推送教程

## 1.1标准格式添加新文章
* 在 `_posts` 目录中新建`.md`文件
* 文件名格式为`YYYY-MM-DD-name-of-post.md`
* 新标准文章内容添加标题
`layout: post`
`title:  "TEST"`
`date:   2022-11-22 15:06:00 +0530`
## 1.2非标格式添加新文章（不推荐）
* 在 `_posts` 目录中新建`.md`文件
* 文件名格式为`YYYY-MM-DD-name-of-post.md`

# 二、特殊功能
## 2.1代码片段 指定语言语法高亮
    {% highlight python %}
    print("Hello World!")
    {% endhighlight %}
## 2.2代码片段
    {% highlight html %}
    print("Hello World!")
    {% endhighlight %}
## 2.3引用图片
![示例文章]({{site.baseurl}}/assets/images/image-3.png)