# 湖南大学实验——图书管理系统
													作者：王雨梦，伍淇铨

## 题目要求 
----
H大学图书馆邀请你建立一个图书馆信息管理系统。请使用面向对象思想完成该问题，具体要求如下：

一、设计一款**文字式交互**的图书管理系统；

二、图书馆必须支持至少10000册书存储，如果课实现书籍可动态增长，加分

三、图书信息包含：
 * 题名
 * ISBN/ISSN
 * 作者
 * 分类号（分类规则自定，要求有三级分类，可参考中图分类法）

四、图书馆系统提供两种用户模式，请为他们设计不同的用户类：
1）管理员模式：
* 系统最初提供一个默认的管理员账户以及默认密码；
* 管理员具备以下功能：
> 可以使用管理员账号登录
> 支持对学校用户的账号进行基本管理，添加、删除学校用户默认账号和密码，默认账号为学号/教师编号，密码为123456；恢复学校用户默认密码
> 管理员可以对图书信息进行修改
> 管理员可以增加、删除、**搜索图书**

2）学校用户模式（学校用户超过5千人）：
* 学校用户可以通过账号和密码登录，账号为学号/教师编号，密码为123456;
* 学校用户可以修改自己的密码
* 学校用户可以搜索图书
* 学校用户可以借、还图书
* 学校用户可以查看自己的借阅记录

五、设计图书馆类，包含馆藏图书列表、用户列表等成员、在馆记录、用户借阅记录等。

六、图书馆系统提供根据**任一信息**的搜索图书功能：
* 题名，精确查找到书
* ISBN/ISSN，精确查找到书
* 作者，模糊查找到该作者所有书，字典序排序
* 分类号，三级分类，每一级分类均可模糊查找到书，字典序排序，按页显示；如，N 自然科学总论——TP 自动化技术、计算机技术——TP3 计算机技术。
* 在以上每一级时，均会出现该级所有数目，字典排序，按页显示；
* **搜索不考察性能，仅考察功能**

七、加分项（总分不超过100分）
* 支持大数据，比如书籍记录突破百万，用户数量突破万级规模；
* 贴近实际的图书馆管理系统，新增若干功能等；
* 实现文件的创建、读、写等操作；
* 考虑用户体验，如使用方便度等；
* 搜索时性能考察，调查、思考、设计加强搜索性能的方式，此项仅适合学有余力的同学；
 
八、完成进度与考核安排：
* 第一阶段，需要完成一万的图书存储；该功能需要至少设计并完成图书类与图书馆系统类的相关部分（包括相关实验报告、代码和测试）；分数占比40%
* 第二阶段，完成两种用户模式，欠搜索功能（包括相关实验报告、代码和测试）；分数占比40%
* 第三阶段，搜索功能（包括相关实验报告、代码和测试）；知识点：文件、排序；分数占比20%
---


