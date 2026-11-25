# weread-mini-update

微信读书小窗（WeReadMini）的在线配置，程序启动后会读取这里的文件：

- `version.json`：检查新版本（`version`/`url`/`notes` 给 Windows，`mac` 段给 Mac）
- `group.json` + `group/`：用户交流群二维码（`qr` 图片路径、`expires` 过期日期）

国内经 jsDelivr 镜像读取：`https://cdn.jsdelivr.net/gh/eightttttt/weread-mini-update@main/version.json`
