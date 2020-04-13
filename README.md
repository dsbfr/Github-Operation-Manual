# GitHub的ReadMe.md文档编辑语法

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
#### ![](图片地址）
![](http://upload-images.jianshu.io/upload_images/1874524-b9be15e31c25eba2.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 插入网络图片二
![表情包](https://raw.githubusercontent.com/wangzchao/Github-Operation-Manual/master/%E5%9B%BE%E7%89%87%E6%B5%8B%E8%AF%95/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20200413220346.png)

#插入本地图片
1、在github上的仓库建立一个存放图片的文件夹，文件夹名字随意。

2、将需要在READNE.md中显示的图片，上传到文件夹中。

3、然后打开github官网，进入仓库的文件夹中，打开图片,点击【Download】按钮，copy地址。

4、在README.md中填入：
#####![Image text](https://raw.githubusercontent.com/wangzchao/Github-Operation-Manual/master/%E5%9B%BE%E7%89%87%E6%B5%8B%E8%AF%95/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20200413220346.png)

保存即可。

# 插入单行引用
>文字

# 单行代码引用
`hellow world`

# 多行代码引用
在代码前后加上```，格式：‘ ```代码``` ’
例如：

‘'''    let pauseBtn = UIButton(frame: CGRect(x: 50, y: HEIGHT-100, width: 100, height: 50))
        pauseBtn.addTarget(self, action: #selector(btnClick(_:)), for: .touchUpInside)
        pauseBtn.setTitle("暂停", for: .normal)
        pauseBtn.tag = 11
        pauseBtn.setTitleColor(UIColor.black, for: .normal)'''’

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
 
