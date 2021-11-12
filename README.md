# my-first-repository
## test markdown
### 三级标题
**加粗文字**
*文字斜体* 
***加粗和斜体***
~~加上删除线~~
>这是引用的内容
>>这是二级引用
***
![picture](https://www.planetware.com/wpimages/2020/02/france-in-pictures-beautiful-places-to-photograph-eiffel-tower.jpg 'picture is good')  
[百度](http://baidu.com)  
<a herf="http://www.baiduom">百度</a>  
- li 1
- li 2
- li 3

|name|rank|score|
|----|:--:|----:|
|zhangsan|1|88|
|lisi|2|89|
|wangwu|3|91|

```
import pandas as pd 
import numpy as np
```



```flow
st=>start: 开始
e=>end: 登录
io1=>inputoutput: 输入用户名密码
sub1=>subroutine: 数据库查询子类
cond=>condition: 是否有此用户
cond2=>condition: 密码是否正确
op=>operation: 读入用户信息

st->io1->sub1->cond
cond(yes,right)->cond2
cond(no)->io1(right)
cond2(yes,right)->op->e
cond2(no)->io1
```



 
人喝水会死[^book]  
hello world   
