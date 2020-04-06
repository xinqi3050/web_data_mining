# web_data_mining
### week 02

## 本周内容及学习目标

1. 使用 requests-html 爬取并存取网页文字档，查找[requests-html 中文文档](https://cncert.github.io/requests-html-doc-cn/#/)
2. 熟悉 [xpath 语法](https://www.w3cschool.cn/xpath/xpath-syntax.html)丶[xpath 节点](https://www.w3cschool.cn/xpath/xpath-nodes.html)
3. 使用 [xpath cheatsheet](https://devhints.io/xpath)
  * 在 Chrome Inspector 使用
  * 在 requests-html (Python) 使用
4. 简易使用 [pd.DataFrame]()

实践
* 解析简单HTML页面
* 使用xpath（不挑greedy vs. 及挑剔ungreedy的策略）
* 获取标签tags丶属性attributes丶值values

实践过程的心得总结：
（1）解析简单HTML页面，要注意greedy 所有<html> 元素标签。
（2）xpath是一门在XML文档（包括html，以樹狀為主的純本文結構文檔）中查找信息的语言。
