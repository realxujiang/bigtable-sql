## Home
访问我的[个人博客Itweet](http://www.itweet.cn),获取更多云计算/大数据的技术文章！

## bigtable-sql-3.5.0
 此软件为基于SQuirreL SQL开源软件二次开发！
 分布式大数据SQL查询可视化界面！
 中文用户手册[请点击](http://www.itweet.cn).

## 编译环境
* Windows or Linux
* Java 8, 64-bit
* Maven 3.1.1+ (for building)

## 支持组件
* hive
* impala
* sparksql
* presto
* drill
* sql on hbase

<div style="text-align:center;"><img src="https://github.com/itweet/bigtable-sql/blob/master/screenshots/bigtable-sql.png" style="vertical-align:middle;"/></div>

## 注意
   presto 所支持的jdk为1.8+,即如果该客户端使用的不是1.8+,则无法连接！提供的bigtable-sql-3.5.0.zip安装包,自带一个jdk1.8,
   即使系统安装了其他版本jdk或者没有安装jdk也能完美运行！

## 编译bigtable-sql
* bigtable-sql是一个标准的maven project,在工程的根目录执行以下命令进行编译:
    - mvn clean install -DskipTests
* 通过导入项目到eclipse编译：
    - 选中项目mvn install

## 运行
  **  unzip bigtable-sql-3.5.0.zip
  - run bigtable-sql.bat

  ** 导入eclipse
    - 等待maven从中央参考下载包,手动添加lib/bigtable-sql_zh_CN.jar到classpatch中
    - crtl+shift+t--Main--Run as--Java Application
