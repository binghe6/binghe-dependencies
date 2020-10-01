# 功能说明
依赖版本管理



## mapstruct用法

![mapstruct使用示例](..\myfile\mapstruct使用示例.jpg)

**org.mapstruct.Mapping**注解用来声明成员属性的映射。这里以成员变量的参数名为依据，如果有嵌套比如Car里面有个CarType类型的成员变量type，其type属性 来映射CarDTO中的type字符串，我们使用type.type 来获取属性值。位置且名称完全一致的字段，所以可以省略。