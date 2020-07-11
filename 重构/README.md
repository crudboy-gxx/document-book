# 重构

## 2 重构原则

何为重构

为何重构

何时重构

怎么对经理说

重构的难题

重构与设计

重构与性能

重构起源何处

## 3 代码的坏味道

3.1 Duplicated Code 重复代码 

3.2 Long Method 过长函数

3.3 Large Class 过大的类

3.4 Long Parameter List 过长参数列

3.5 Divergent Change 发散式变化

3.6 Shotgun Surgery 散弹式修改

3.7 Feature Envy 依恋情结

3.8 Data Clumps 数据泥团

3.9 Primitive Obsession 基本类型偏执

3.10 Switch Statements switch惊悚现身

3.11 Parallel Inheritance Hierarchies 平行继承体系

3.12 Lazy Class 冗赘类

3.13 Speculative Generality 夸夸其谈未来性

3.14 Temporary Field 令人迷惑的暂时字段

3.15 Message Chains 过度耦合的消息链

3.16 Middle Man 中间人

3.17 Inappropriate Intimacy 不适当的亲昵关系

3.18 Altemative Classse With Different Interface 异曲同工的类

3.19 Incomplete Library Class 不完美的类库

3.20Data Class 纯粹的数据类型

3.21 Refused Bequest 被拒绝的遗赠

3.22 Comments 过多的注释

## 4 构筑测试体系

4.1 自测试代码的价值

4.2 JUnit测试框架

4.3 添加更多测试

## 5 重构列表

5.1 重构的记录格式

5.2 寻找引用点

5.3 这些重构收发有多成熟

## 6 重新组织函数

6.1 Extract Method 提炼函数

6.2 Inline Method 内联函数

6.3 Inline Temp内联临时变量

6.4 Replace Temp with Query 以查询取代临时变量

6.5 Introduce Explaining Variable 引入解释性变量

6.6 Split Temporary Variable 分解临时变量

6.7 Remove Assignments to Parameters 移除对参数的赋值

6.8 Replace Method with Method Object 以函数对象取代函数

6.9 Substitute Algorithm 替换算法

## 7 在对象之间搬移特性

7.1 Move Method 搬移函数

7.2 Move Field 搬移字段

7.3 Extract Class 提炼类

7.4 Inline Class 将类内联化

7.5 Hide Delegate 隐藏委托关系

7.6 Remove Middle Man 移除中间人

7.7 Introduce Foreign Method 引入外加函数

7.8 Introduce Local Extension 引入本地扩展

## 8 重新组织数据

8.1 Self Encapsulate Field 自封装字段

8.2 Replace Data Value with Object 以对象取代数据值

8.3 Change Value to Reference 将值对象改为引用对象

8.4 Change Reference to Value 将引用对象改为值对象

8.5 Replace Array with Object 以对象取代数组

8.6 Duplicate Observed Data 复制被监视数据

8.7 Change Unidirectional Association to Bidirectional 将单向关联改为双向关联

8.8 Change Bidirectional Association to Unidirectional 将双向关联改为单向关联

8.9 Replace Magic Number with Symbolic Constant 以字面常量取代魔法数

8.10 Encapsulate Field 封装字段

8.11 Encapsulate Collection 封装集合

8.12 Replace Record with Data Class 以数据类取代记录

8.13 Replace Type Code with Class 以类取代类型码

8.14 Replace Type Code with Subclasses 以子类取代类型吗

8.15 Replace Type Code with State/Strategy 以State/Strategy取代类型码

8.16 Replace Subclass with Fields 以字段取代子类

## 9 简化条件表达式

9.1 Decompose Conditional 分解条件表达式

9.2 Consolidate Conditional Expression 合并重复的条件片段

9.3 Remove Control Flag 移除控制标记

9.4 Replace Nested Conditional with Guard Clauses 以卫语句取代嵌套条件表达式

9.5 Replace Conditional with Polymorphism 以多态取代条件表达式

9.6 Introduce Null Object 引入Null对象

9.7 Introduce Assertion 引入断言

## 10 简化函数调用

10.1 Rename Method 函数改名

10.2 Add Parameter 添加参数

10.3 Remove Parameter 移除参数

10.4 Separate Query from Modifier 将查询函数和修改函数分离

10.5 Parameterize Method 令函数携带参数

10.6 Replace Parameter with Explicit Methods 以明确函数取代参数

10.7 Preserve Whole Object 保持对象完整

10.8 Replace Parameter with Methods 以函数取代参数

10.9 Introduce Parameter Object 引入参数对象

10.10 Remove Setting Method 移除设值函数

10.11 Hide Method 隐藏函数

10.12 Replace Constructor with Factory Method 以工厂函数取代构造函数

10.13 Encapsulate Downcast 封装向下转型

10.14 Replace Error Code with Exception 以异常取代错误代码

10.15 Replace Exception with Test 以测试取代异常

## 11 处理概括关系

11.1 Pull Up Field 字段上移

11.2 Pull Up Method 函数上移

11.3 Pull Up Constructor Body 构造函数本体上移

11.4 Push Down Method 函数下移

11.5 Push Down Field 字段下移

11.6 Extract Subclass 提炼字段

11.7 Extract Superclass 提炼超类

11.8 Extract Interface 提炼接口

11.9 Collapse Hierarchy 折叠继承体系

11.10 From Template Method 塑造模板函数

11.11 Replace Inheritance with Delegation 以委托取代继承

11.12 Replace Delegation  with Inheritance 以继承取代委托

## 12 大型重构

12.1 Tease Apart Inheritance 梳理并分解继承体系

12.2 Convert Procedural Design to Object 将过程话设计转化为对象设计

12.3 Separate Domain from Presentation 将领域和表述/显示分离

12.4 Extract Hierarchy 提炼继承体系

## 13 重构，复用与现实

13.1 现实的检验

13.2 为什么开发者不愿意重构他们的程序

13.3 再论现实的检验

13.4 重构的资源和参考资料

13.5 从重构联想到软件复用和技术传播

## 14 重构工具

14.1 使用工具进行重构

14.2 重构工具的技术标准

14.3 重构工具的实用标准

## 15 总结

