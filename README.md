# 文件下载器

通过命令行下载指定 URL 的文件，支持多线程并发下载。

---

## 依赖

本程序依赖以下第三方包：

> github.com/urfave/cli/v2
> github.com/schollz/progressbar/v3

## 使用方法

在命令行中输入以下命令：

```shell
go run . --url [url]

示例: go run . --url https://archive.apache.org/dist/zookeeper/zookeeper-3.4.6/zookeeper-3.4.6.tar.gz
```


## License

This project is MIT licensed. See the [LICENSE](https://github.com/haoel/ipsearch/blob/main/LICENSE) file for details.