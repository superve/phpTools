# phpTools
工作和学习中积累下来的常用的php扩展函数，解决开发效率问题(过程版)
##说明
1. 创建时间:2015/10/04，本函数库用于交流和学习，欢迎使用以及提出改进建议
2. 此功能库于2015/10/04开始整理，总结和重写了工作中常用的PHP函数，使部分函数更具通用化，更适合于一般情况 
3. 库文件名为tools.php,配套的测试文件(样例文件)名为toolsTest.php  
4. 函数命名规范为小驼峰法  
5. 库文件中的函数是自说明的，说明文档DOC.md只是归类，提供一个大纲视图
6. 上次修改时间:2015/11/01

##ChangeLogs
9. [2015/11/01 12:39]
在isDecimalValid()函数中考虑了实时输入实数时，对出现"12."的情况的验证(用户时按退格删除数字)
8. [2015/11/01 10:44]
为isDecimalValid()函数增加了一个参数合法性判断(不允许包含除.和0-9的字符)
7. [2015/10/15 8:19]  
添加了aryRearrange()中排除参数为空的情况
6. [2015/10/09 13:41]  
<解决PROBLEMS-1>将所有递归函数中，使用staic返回属组，全部改用常规数组。如 hHirarchify、hGetDescendantIds、hTraceRoot
5. [2015/10/09 10:55]  
将dumpf()改进为支持变参函数
4. [2015/10/07 17:29]  
为了适应TP框架中的验证回调函数，将所有的验证函数，都改为合法返回true,不合法返回false。之前是合法返回1,不合法返回0
3. [2015/10/06 10:10]  
调整了hHirarchify()函数和vHirarchify()函数_cateInfo,_excludeIds的位置将它们对换了一下
2. [2015/10/04 23:07]  
将fileRawname($_uri)更名为getBasename($_uri),可以获得文件名/目录/url/带查询字符串的url的基名
1. [2015/10/04 22:20]  
将entityHTMLTag($_html, $_tag)更名为entitifyTags($_html, $_tags),可以同时将一段HTML中的多个指定的标签实体化  
