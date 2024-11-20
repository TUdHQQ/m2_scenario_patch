# m2_scenario_patch
 a simple program to patch the texts of m2 scenario

# 如何使用

首先用[FreeMote](https://github.com/UlyssesWu/FreeMote/releases/tag/v3.7.0)解包文件
测试版本: v3.7.0

然后对于提取出来的每个剧本文件使用如下命令提取文本(确保目录下没有patch.json)

```
m2_t xxx.json
````

文本就会输出在out.json下

接着汉化out.json的内容, 并将其重命名成patch.json
再执行一次

```
m2_t xxx.json
````

结果就会保存在 result.json 中

有关savejson: 可以把你原来的json文件进行格式化, 输出为qwq.json, 方便你比较差异
