---
sidebar_position: 1
---

# 基本配置
所有账号的必填项
### name（名称）
唯一标识符，也是当有多个账号时展示的路径
### index（索引）
当有多个账号时，用于排序，越小越靠前
### proxy（代理）
是否允许服务器中转下载，默认需要走中转的不会有此项，如本地存储和谷歌云盘。
只是是否允许代理下载，前端所有的预览和复制下载链接什么的都是直接从网盘下载，将复制的下载链接中的/d改成/p就是通过代理下载，关闭了之后/p会提示不允许，打开通过这个链接就可以通过服务器中转下载。