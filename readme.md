
# 运行

cd到项目的根目录,执行以下命令

```
mvn clean install
cd webapp
mvn jetty:run 
```


# 生成工程文件
## Eclipse
```
mvn eclipse:eclipse
```
## Intellij Idea

使用以下命令生成的是旧版本的项目文件，不推荐。其实用idea打开项目文件夹就会自动生成项目文件了。

```
mvn idea:idea
```