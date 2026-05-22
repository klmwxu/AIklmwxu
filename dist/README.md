# 货袋子 · 积分 & 会员 · 原型与文档打包下载

> 版本：v1.1（含企业 4 级会员体系：普通 / 银卡 / 金卡 / 铂金卡）
> 内容：`docs/` 规则文档 + `prototypes/` 4 个 HTML 原型 + README

## 下载

直接点击同目录下的 `huodaizi-积分会员-原型与文档-v1.1-YYYYMMDD.zip`，GitHub 默认会以"下载"方式触发。

或者在终端：

```bash
# Linux / macOS
wget "https://github.com/klmwxu/AI./raw/cursor/membership-enterprise-tiers-484d/dist/<文件名>.zip"
```

```powershell
# Windows PowerShell
Invoke-WebRequest "https://github.com/klmwxu/AI./raw/cursor/membership-enterprise-tiers-484d/dist/<文件名>.zip" -OutFile "huodaizi.zip"
```

## 解压后目录结构

```
huodaizi-积分会员-原型与文档-v1.1-YYYYMMDD/
├── docs/
│   └── 积分体系-动作清单与规则设计.md
└── prototypes/
    ├── index.html         (入口导航)
    ├── admin.html         (运营后台)
    ├── user.html          (个人积分中心)
    ├── enterprise.html    (企业积分中心)
    └── README.md          (原型说明)
```

## 使用

双击 `prototypes/index.html` 即可在浏览器中预览整套原型。首次需联网加载 Tailwind 与 ECharts CDN（约 200KB）。
