# 一、基本功能

```java
reference:
https://blog.csdn.net/m0_57787115/article/details/130296388
```



## 1、克隆仓库

```bash
git clone  https://github.com/Whitejun/DevEnvironment.git
```



## 2、添加和提交代码

使用`git commit`命令提交更改到本地仓库，并提供相关的提交说明

```bash
git commit -m "第一版提交测试"
```



## 3、推送代码

使用`git push`命令将本地仓库的代码推送到GitHub远程仓库。

```bash
git push origin main
```





# 二、Git 命令行

## 1、上传项目

```java
# 先提交到缓冲区
git add 'How to use Github.md'
# git commit将暂存区的项目提交到本地仓库，注意，该行为会被记录，-m后面加该行为的备注，以提示自己或他人。
git commit -m "我上传了第一个项目"

# git push用于将本地仓库的更改推送到远程仓库，也就是github官网上我们自己的仓库
git push origin main



```

