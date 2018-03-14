# JSONObject
Java servlet 解析json所需的jar包

JSONObject:A JSONObject is an unordered collection of name/value pairs.

是一个final类，继承了Object，实现了JSON接口

构造方法如下：

JSONObject();创建一个空的JSONObject对象

JSONObject(boolean isNull);创建一个是否为空的JSONObject对象

普通方法如下：

fromBean(Object bean);静态方法,通过一个pojo对象创建一个JSONObject对象

fromJSONObject(JSONObject object);静态方法,通过另外一个JSONObject对象构造一个JSONObject对象

fromJSONString(JSONString string);静态方法,通过一个JSONString创建一个JSONObject对象

toString();把JSONObject对象转换为json格式的字符串

iterator();返回一个Iterator对象来遍历元素
