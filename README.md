# MongoDB

- 文档
 `保留字符：$ . 下划线开头 不能是空  不能还有空字符`
- 集合
 `集合就是一组文档  文档类似于JavaScript中的 对象`
- 子集合
 `组织集合的惯例是使用"."字符分开的按命名空间划分子集 如：blog博客可能包含两个集合 分别是：blog.posts  blog.authorrs    也就是说这里根本不需要blog 这个集合  同事blog 集合与子集合也没有任何关系 （shell中 db.blog 代表 blog 集合   db.blog.posts 代表 blog.posts 集合）`
- 保留的数据库名称
 `admin local config`
  * admin -- 里面负责权限 ||| local -- 里面的东西不会被复制 |||  config - 共享 *
 