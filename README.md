# Java · 2021 课程练习

2021 年上半年 Java 课的按周作业，14 个目录（`Week1` … `Week14`），每周几个独立的 `.java` 文件。

内容是循序渐进的课堂练习：早期是基本语法、类与对象、集合；中段开始出现 Swing 图形界面（`Frame`、`Music`、`Machine` 一类的小程序）；后段是 JDBC 数据访问（`DbConnection`、`Driver`、`StudentDao`）。

## 怎么看

每个目录都是独立的小项目，没有统一构建脚本。单个文件可以直接编译运行：

```bash
javac Week14/*.java -d out
java -cp out Driver
```

含数据库的几周需要本地有一个可用的数据库连接（`DbConnection` 里写着连接串），否则只能读代码。

## 说明

- 学生作业原样保留，没有重构、没有补测试。
- 想看我目前在维护的项目，请到这里：<https://github.com/Glorious-Force/cyanide-site>