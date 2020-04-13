# GitHub的ReadMe.md文档编辑语法
#### README文件后缀名为md。md是markdown的缩写，markdown是一种编辑博客的语言。不过GitHub支持的语法在标准markdown语法的基础上做了修改，称为Github Flavored Markdown，简称GFM。

作者：MillerWang
链接：https://www.jianshu.com/p/9ab92efc286a
来源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

#六级标题的字体大小
# 一级标题 【注意：字和#号之间要有空格】
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

# 无序列表
  - 文本1
  - 文本2
  
# 有序列表
  1.文本1
  
  2.文本2
  
# 插入网络链接
[简书](http://www.baidu.com "悬停显示文字")

# 插入网络图片一
#### 即 叹号! + 方括号[ ] + 括号( ) 其中叹号里是图片的URL
![](http://upload-images.jianshu.io/upload_images/1874524-b9be15e31c25eba2.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 插入网络图片二
![表情包](https://raw.githubusercontent.com/wangzchao/Github-Operation-Manual/master/%E5%9B%BE%E7%89%87%E6%B5%8B%E8%AF%95/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20200413220346.png)

#插入本地图片
1、在github上的仓库建立一个存放图片的文件夹，文件夹名字随意。

2、将需要在READNE.md中显示的图片，上传到文件夹中。

3、然后打开github官网，进入仓库的文件夹中，打开图片,点击【Download】按钮，copy地址。

4、在README.md中填入：
*![Image text](https://raw.githubusercontent.com/wangzchao/Github-Operation-Manual/master/%E5%9B%BE%E7%89%87%E6%B5%8B%E8%AF%95/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20200413220346.png)*

保存即可。

# 插入单行引用
>文字

# 单行代码引用
`hellow world`

# 多行代码引用
#### 我们需要在代码的上一行和下一行用'''标记。注意，'''不是三个单引号，而是数字1左边，Tab键上面的键。要实现语法高亮那么只要在 ''' 之后加上你的编程语言即可（忽略大小写）。c++语言可以写成c++也可以是cpp。
例如：

```let pauseBtn = UIButton(frame: CGRect(x: 50, y: HEIGHT-100, width: 100, height: 50))```
```pauseBtn.addTarget(self, action: #selector(btnClick(_:)), for: .touchUpInside)```
```pauseBtn.setTitle("暂停", for: .normal)```
```pauseBtn.tag = 11```
```pauseBtn.setTitleColor(UIColor.black, for: .normal)```

# 网络链接
http://www.baidu.com

# 粗体和斜体
*斜体字* 

**粗体字** 

***加粗斜体字***

# 表格格式一
| 表格      | 第一列     | 第二列     |
| ---------- | :-----------:  | :-----------: |
| 第一行     | 第一列     | 第二列     |

# 表格格式二
 表格      | 第一列     | 第二列     
 -------- | :-----------:  | :-----------: 
 第一行     | 第一列     | 第二列   
 
 # 分割线
 ***
 
 # 删除线
 ~~删除~~
 
# 缩进

>数据结构  
>>树  
>>>二叉树  
>>>>平衡二叉树  
>>>>>满二叉树  
