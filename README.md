北京挂号平台脚本
==

* 本程序用于 [北京市预约挂号统一平台](http://www.bjguahao.gov.cn/)  的挂号。只支持北京地区医院的挂号。
*  挂号是刚需。帝都有些医院号源紧张，放号瞬间被秒杀一空，遂产生了撸一脚本挂号的念头。说干就干，简单的分析和调试后于16年8月份左右产出第一版，顺利挂上了XXX院运动医学科的号。很开心。
*  17年2月底的时候，朋友也需要挂一个号，脚本给他改了改，貌似删了重写的？没有仔细看。经过精心的分析和调试，挂了一个专家号。很开心。
*  17年3月8号，两位热心网友github上发起issues，提出反馈，让我很意外。本来想着这脚本自己写着用就可以了。接到反馈后觉得可以写成一个成熟的软件了。两位热心网友也主动提出改进代码的愿望。很开心。
*  __还看什么看，来贡献代码__ ;-)

`2017-03-08 17:12:20 breaker`

### 配置文件

在脚本目录将`_config.josn`重命名为`config.json`, 然后写入如下数据

```json
{
    "username":"185xxxxxxx",
    "password":"*******",
    "date":"2017-02-17",            # 挂号日期
    "hospitalId":"142",             # 142 北医三院
    "departmentId":"200039584"      # 运动医学科

}
```

### 文档
[文档](doc.md)中有比较详细的接口分析和装包
