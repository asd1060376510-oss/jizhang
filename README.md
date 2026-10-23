# jizhang

这个仓库只用来发布记账 App 的安装包，通过 GitHub Release 提供下载。

- 最新版本见 [Releases](https://github.com/asd1060376510-oss/jizhang/releases)
- App 内置自动更新，会从这里拉取 APK
- 不放任何源码

## 发版流程

```bash
export GITHUB_TOKEN=ghp_xxx
python tools/publish_github.py --apk dist/jizhang-x.y.z.apk --tag vx.y.z --notes "更新说明"
```
