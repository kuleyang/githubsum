# Github Checksums

这是一个小工具，读取Github仓库tags、提交或者是分支tar包的checksums。
用于更新Macports的Portfiles文件中的checksums，非常方便


## 用法

checksums 一个仓库的例子：

```
githubsum kuleyang githubsum v0.2.0
```

将会打印出sha256和rmd160：

```
file: ~/Downloads/kuleyang-githubsum-v0.2.0.tar.gz
sha256: 133af3abcc080e128cd411c9349b0a9b8367768efd586081d13b61485595ebe3
rmd160: a779716d0f46cd6d4b29908ef3982cedc72d9e61
```

## 安装

把Portfile放入你的本地仓库,然后

```
sudo portindex
sudo port install githubsum
```

