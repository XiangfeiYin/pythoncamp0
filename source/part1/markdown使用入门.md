#Markdown 使用入门

##编辑器选择
推荐haroopad  
理由：　　
- 多种主题
- 左侧可显示语法
- 中文界面
- 跨平台

不推荐retext 下载之后的功能不完整，貌似要安装拓展，没有实时预览。　　


###标题
 # 和「一级标题」之间建议保留一个字符的空格，这是最标准的 Markdown 写法。
###换行
在文本中输入的换行会从最终生成的结果中删除，浏览器会根据可用空间自动换行。如果想强迫换行，可以在行尾插入至少两个空格。
最简单的方法，在行尾插入至少两个空格：  
换行   
换行
###列表
无序列表  
+ lineone
+ linetwo  
- lineone
- linetwo  
有序列表  
1.  lineone
2.  linetwo  

###引用
> If you can not explain it simply, you do not understand it well enough.------Albert.Einstein.  
 *If you can not exmakmarplain it simply, you do not understand it well enough.------Albert.Einstein.*  
 
结束引用，空行。
###插入图片
`![](url"title")`  
![](https://totallyinspiredpc.files.wordpress.com/2014/02/wpid-99359c0ec8b3bf2a9ff4f7336cf64f9f.jpg?w=593"Einstein")


###插入代码
/用反引号``  

`code`  
```
#timer
def replaysetup():
    global step, shape_list, click_count, history_list
    shape_list =[]
    if step < click_count:
        step += 1
        for history_step in range(0,step):
            shape_list.append(history_list[history_step])
    else:
        step = 0```
        
        