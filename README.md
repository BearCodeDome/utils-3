# utils
基于单例模式,惰性求值思想,使用原生JS封装的兼容IE6~8的常用DOM库

## 使用方法
引入 utils.js
utils.方法名(参数1,参数2,...)

### 方法
listToArray(把类数组集合转换为数组)

formatJSON(把JSON格式字符串转换为JSON格式对象)

offset(获取页面中任意元素距离BODY的偏移)

win(操作浏览器的盒子模型信息)

children(获取所有的元素子节点)

prev(获取上一个哥哥元素节点)

next(获取下一个弟弟元素节点)

prevAll(获取所有的哥哥元素节点)

nextAll(获取所有的弟弟元素节点)

sibling(获取相邻的两个元素节点)

siblings(获取所有的兄弟元素节点)

index(获取当前元素的索引)

firstChild(获取第一个元素子节点)

lastChild(获取最后一个元素子节点)

prepend(向指定容器的开头追加元素)

insertBefore(把新元素newEle追加到指定元素oldEle的前面)

insertAfter(把新元素newEle追加到指定元素oldEle的后面)

hasClass(验证当前元素中是否包含className这个样式类名)

addClass(给元素增加样式类名)

removeClass(给元素移除样式类名)

getElementsByClass(通过元素的样式类名获取一组元素集合)

css(此方法实现了获取、单独设置、批量设置元素的样式值)