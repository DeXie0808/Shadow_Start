# Shadow_Start
I am iron man!

<table width="100%">
<tr>
<td><img src="pics/chicken you are so beautiful.jpg", alt="Mountain View" width="95%"></td>
</tr>
</table>



## Recent plan

**Note:** must be done!

*  read paper and implement some open source codes!

		OB:faster-rcnn, yolo,yolo2,yolo3, mask-rcnn……
		PE:PAF（tf+pyorch+mxnet），capsuleNet-pt
* deep and-or model

		Introduce (https://m.aliyun.com/yunqi/articles/293634),  
		Code (https://github.com/xilaili/AOGNet)
* mxnet+gloun
* keras+tensorflow
* Docker
* cython
* cupy
* [pyramid Attention Network]( https://www.jiqizhixin.com/articles/pyramid-attention-network?from=synced&keywords=%E8%AF%AD%E4%B9%89%E5%88%86%E5%89%B2)
* opencv（python与C++）
* 图论，图学习，图卷积
* 可变形卷积
* 可分离卷积
* Non_Local **(Done)**
* This is test


## Markdown 语法介绍
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

> Coding.net
> 
> 这是第一级引用。
>
> > 这是第二级引用。
>
> 现在回到第一级引用。

> ## 这是一个标题。
> 1. 这是第一行列表项。
> 2. 这是第二行列表项。
>
> 给出一些例子代码：
>
> return shell_exec(`echo $input | $markdown_script`);

- Red
- Green
- Blue

- [ ] 不勾选
- [x] 勾选

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right


这是分隔线上部分内容
---
这是分隔线上部分内容

```graph
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->E;
    E-->F;
    D-->F;
    F-->G;
```

```graph
sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts 
prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
```

```graph
gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
```