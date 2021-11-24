---
sidebar_position: 3
---

# 阿里云盘

:::tip

由于阿里云盘referrer的限制，必须使用移动端token，使用桌面web端token会导致无法下载与预览。

:::

### refresh_token（刷新令牌）
如何获取参考这个[issue](https://github.com/Xhofe/alist/issues/88)通过手机端抓包/查找日志（/data/media/0/Android/data/com.alicloud.databox/files/logs/trace/）来获取,或使用https://media.cooluc.com/decode_token/
### 排序与排序方向
自行选择，或者不选
### 根目录file_id
打开阿里云盘官网，点进去你要设置的文件夹时url后面的一串，如https://www.aliyundrive.com/drive/folder/5fe01e1830601baf774e4827a9fb8fb2b5bf7940就是5fe01e1830601baf774e4827a9fb8fb2b5bf7940
![file_id](https://store.heytapimage.com/cdo-portal/feedback/202111/24/e69c2d064d6794fc008c7ba1588707da.png)

### 限制
如果你的服务器与阿里云盘的服务器通信困难，可选择填小一点，否则默认不填就好