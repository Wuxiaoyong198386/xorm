Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@Wuxiaoyong198386 Sign out
241
4,548 580 go-xorm/xorm
 Code  Issues 222  Pull requests 33  Projects 0  Wiki  Insights
You’re editing a file in a project you don’t have write access to. We’ve created a fork of this project for you to commit your proposed changes to. Submitting a change to this file will write it to a new branch in your fork, so you can send a pull request.
xorm
/
README_CN.md
or cancel
  
1
# xorm
2
​
3
[English](https://github.com/go-xorm/xorm/blob/master/README.md)
4
​
5
xorm是一个简单而强大的Go语言ORM库. 通过它可以使数据库操作非常简便。
6
​
7
[![CircleCI](https://circleci.com/gh/go-xorm/xorm.svg?style=shield)](https://circleci.com/gh/go-xorm/xorm) [![codecov](https://codecov.io/gh/go-xorm/xorm/branch/master/graph/badge.svg)](https://codecov.io/gh/go-xorm/xorm)
8
[![](https://goreportcard.com/badge/github.com/go-xorm/xorm)](https://goreportcard.com/report/github.com/go-xorm/xorm)
9
[![Join the chat at https://img.shields.io/discord/323460943201959939.svg](https://img.shields.io/discord/323460943201959939.svg)](https://discord.gg/HuR2CF3)
10
​
11
## 特性
12
​
13
* 支持Struct和数据库表之间的灵活映射，并支持自动同步
14
​
15
* 事务支持
16
​
17
* 同时支持原始SQL语句和ORM操作的混合执行
18
​
19
* 使用连写来简化调用
20
​
21
* 支持使用Id, In, Where, Limit, Join, Having, Table, Sql, Cols等函数和结构体等方式作为条件
22
​
23
* 支持级联加载Struct
24
​
25
* Schema支持（仅Postgres）
26
​
27
* 支持缓存
28
​
29
* 支持根据数据库自动生成xorm的结构体
30
​
31
* 支持记录版本（即乐观锁）
32
​
33
* 内置SQL Builder支持
34
​
35
* 上下文缓存支持
36
​
37
## 驱动支持
38
​
39
目前支持的Go数据库驱动和对应的数据库如下：
40
​
41
* Mysql: [github.com/go-sql-driver/mysql](https://github.com/go-sql-driver/mysql)
42
​
43
* MyMysql: [github.com/ziutek/mymysql/godrv](https://github.com/ziutek/mymysql/godrv)
44
​
45
* Postgres: [github.com/lib/pq](https://github.com/lib/pq)
46
​
47
* Tidb: [github.com/pingcap/tidb](https://github.com/pingcap/tidb)
@Wuxiaoyong198386
Propose file change
Commit summary 
Update README_CN.md
Optional extended description
Add an optional extended description…
 
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
