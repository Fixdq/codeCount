#### 统计zip包下项目的python代码

##### 功能
1. 文件上传
2. 跳转页面，显示统计结果
3. ajax异步请求显示统计结果

##### 缺陷
1. 无法统计特殊的块注释
>eg：

>def func01():'''
    注释。。。
    '''

2. 无法统计代码和注释在一行的注释行数
>eg：

>x= 100  # 这是一个x坐标