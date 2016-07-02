## commons-lang3

---

**主要是提供一些基础的操作和处理，归为以下几类：**

*	org.apache.commons.lang3（高度重用的Util类，常用的工具类静态方法；重点）

*	org.apache.commons.lang3.builder（忽略）

*	org.apache.commons.lang3.concurrent（忽略）

*	org.apache.commons.lang3.event（忽略）

*	org.apache.commons.lang3.exception（忽略）

*	org.apache.commons.lang3.math（数字类型转换、大小比较、是否数字 等相关工具类；重点）

*	org.apache.commons.lang3.mutable（包装值型变量，为基础数据类型扩展了更多方法）
	
*	org.apache.commons.lang3.reflect（反射相关，忽略）

*	org.apache.commons.lang3.text（文本相关）

*	org.apache.commons.lang3.time（处理日期和时间的功能；重点）

*	org.apache.commons.lang3.tuple（忽略）


### pom依赖

```
<dependency>
  	<groupId>org.apache.commons</groupId>
  	<artifactId>commons-lang3</artifactId>
  	<version>3.4</version>
</dependency>
```








*	StringEscapeUtils – 用于正确处理转义字符，产生正确的Java、JavaScript、HTML、XML和SQL代码；

*	CharRange – 用于设定字符范围并做相应检查；

*	ClassUtils – 用于对Java类的操作，不使用反射；

*	Validate – 提供验证的操作，有点类似assert断言；

https://commons.apache.org/proper/commons-lang/javadocs/api-release/

http://zhoualine.iteye.com/blog/1770014