# FFmpeg-Win64

从 [Gyan的网站](https://www.gyan.dev/ffmpeg/builds/) 搬运得到，并用 JSdelivr 作为CDN加速，使用工具 [ReleaseDelivr](https://github.com/One-Studio/ReleaseDelivr)

## 最新FFmpeg下载链接：
https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Win64@master/dist/ffmpeg-release-essentials.7z

## 某个版本的下载链接
通过下面的API接口获取历史版本号，比如 `4.3.1-2020-10-01`，下载链接：

https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Win64@4.3.1-2020-10-01/dist/ffmpeg-release-essentials.7z

## 原网站API：
版本号：https://www.gyan.dev/ffmpeg/builds/release-version

下载链接：https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-essentials.7z

## 本搬运仓库API：
版本号：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Win64/version

下载链接（ `/n` 分割）：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Win64/download_link

API接口 Json格式：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Win64/api.json

| API          | 类型     | 含义                                          |
| ------------ | -------- | --------------------------------------------- |
| Version      | string   | 版本号                                        |
| VersionList  | []string | 历史版本                                      |
| ReleaseTime  | string   | 最新版本的发布时间 (格式2020-10-20T12:16:01Z) |
| Checktime    | string   | 搬运时检查的时间                              |
| DownloadLink | []string | 下载链接                                      |
| Format       | int      | 格式(1=7z, 2=zip)                             |
| ReleaseNote  | string   | 更新日志                                      |
