# 糖豆广场舞下载器

在网页内抓取[糖豆广场舞](https://www.tangdou.com/)视频链接，并下载到本地。
~~（其实是母上经常要求下载所以无聊写了这个）~~

![](https://img.shields.io/badge/Python-2.7-brightgreen.svg)

## 功能

- 自动重命名为视频标题
- 支持批量下载
- 支持从文件中读取链接
- 好像再没有了（

## 缺点

- 写得太弱智（废话
- 单线程下载
- 对 Windows 支持可能不友好

## 用法

```shell
tddown.py links | -l list_file [-t dest_path]
```
| 参数 | 用法 |
|---|---|
| `links` | 一个或多个视频页面链接，可以是```www.tangdou.com m.tangdou.com share.tangdou.com``` 。|
| `-t dest_path` | 可选，将下载的文件存储至自定义的位置 `dest_path` 。如果目标不存在，则将创建。 |
| `-l list_file` | 若没有 `links` 则必须提供。读取文件 `list_file` 里的视频页面链接，批量下载。 |

## Collaborator

- [kj415j45](https://github.com/kj415j45)

## Donate

因为太弱了，所以无法接受捐赠。
