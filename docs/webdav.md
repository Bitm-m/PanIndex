## WebDav


配置WebDav连接信息时，要注意**端口号**，是否开启了**https**，文件路径，有些时候路径不需要带前缀`/`，另外有些客户端及网盘对于302的支持不是很好，建议用（本地）方式中转下载。

WebDav客户端，不断测试补充中...

| 客户端                                        | 操作系统        | 说明                                                                                                  | 测试                                                                                                                                                                                                                 |
| ------------------------------------------ | ----------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| win11/win10自带                              | windows     | 1. http支持需要[修改注册表](https://d9.ee/archive/webdav-add-dav.html)<br/>2. 通过使用**映射网络驱动器**添加，而非**添加网络位置** | 小文件通过，超过50M文件无法下载播放（[系统限制](https://support.microsoft.com/en-us/topic/folder-copy-error-message-when-downloading-a-file-that-is-larger-than-50000000-bytes-from-a-web-folder-815e2949-0f56-ec25-db7d-b6d860a31f77)） |
| [raidrive](https://www.raidrive.com.cn/)   | windows     | 免费版有广告                                                                                              | 通过，windows下强烈推荐                                                                                                                                                                                                    |
| [nplayer](https://nplayer.com/)            | ios、android | 一款支持Webdav的播放器，付费，有破解                                                                               | 通过                                                                                                                                                                                                                 |
| [WinSCP](https://winscp.net/eng/index.php) | windows     | 网络文件传输工具                                                                                            | 通过                                                                                                                                                                                                                 |
| 群晖（File Station）                           | 群晖          | 路径前面不能加`/`                                                                                          | 通过                                                                                                                                                                                                                 |


