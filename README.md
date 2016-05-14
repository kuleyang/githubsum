# Github Checksums

这是一个小工具，读取Github仓库tags、提交或者是分支tar包的checksums。
用于更新Macports的Portfiles文件中的checksums，非常方便


## 用法

checksums 一个仓库的例子：

```
githubsum kuleyang/githubsum v0.1.0
```

将会打印出sha256和rmd160：

```
sha256: 863ce994a8a9a276f3ea8a6a395b33015540cccf08c8e419223aa8253ed42eb2
rmd160: 8135a086a7ba075d5ce3596caaa46cd21705bb64
```

## 安装

把Portfile放入你的本地仓库,然后

```
sudo portindex
sudo port install ghsum
```

