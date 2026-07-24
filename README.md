# miniprogmgt-dist

MiniProgMgt 的**公开发布仓**:只存各小程序的编译产物(zip)、`catalog.json` 及其签名。

- **不含源码,不含任何个人姓名 / 工号** —— 所有产物经发布 CI 的姓名 / 路径扫描后才进来。
- `catalog.json` —— 小程序目录清单(总程序读它决定下载什么),由 CI 自动生成 + Ed25519 签名(`catalog.json.sig`)。
- 各小程序的 zip 作为本仓 **Release 资产**发布。

由 `WangYiTao0/MiniProgMgt` 的发布流水线自动维护,一般不手动改。
