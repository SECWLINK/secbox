# SecBox 在线安全工具箱

面向 CTF 竞赛与信息安全学习的浏览器端工具集，共 10 类 56 项工具，全部计算在浏览器本地完成，输入内容不上传服务器。

## 工具分类

| 分类 | 数量 | 内容 |
| --- | --- | --- |
| 编码解码 | 8 | Base64 / Hex / XOR / 进制转换等 |
| 加密算法 | 16 | AES / DES / RSA / 古典密码等 |
| 哈希校验 | 5 | MD5 / SHA256 / CRC32 及哈希爆破 |
| 隐写分析 | 3 | PNG CRC / 文本隐写 / 频域水印分析 |
| 压缩包处理 | 3 | ZIP / 7z 文件分析与循环解压 |
| 流量与 SQL | 2 | OTP 预测、SQL 盲注 payload 生成 |
| 信息收集 | 5 | Favicon 哈希、HTTP 头分析、链接提取 |
| 二维码 | 1 | 二维码生成 |
| 区块链 | 4 | BTC / ETH 地址分析、合约审计、交易追踪 |
| 杂项工具 | 9 | 时间戳 / UUID / ASCII 艺术 / 数学计算等 |

## 部署

纯静态站点，无需后端。将本仓库目录直接作为静态站点根目录发布即可：

```
index.html
assets/
  index-Dm1nKfmZ.js
  rolldown-runtime-C0FnF6B9.js
  radix-SGtrwMXj.js
  toolkit-osEdCH-E.js
  index-CFZgH_jl.css
  polyfills.js
  avatar.png
```

## 说明

- 页面内所有工具在前端运算，不依赖服务器。
- 区块链查询、Favicon 获取等信息收集类工具需访问对应公开接口，网络受限时不可用。
- 本仓库为静态站点镜像，用于提供不依赖第三方平台的长期访问地址。
