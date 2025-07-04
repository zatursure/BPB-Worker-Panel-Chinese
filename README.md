<h1 align="center">BPB 面板 💦</h1>

## ⚠️ 注意事项

> [!WARNING]
> 本项目是原作者[bia-pain-bache](https://github.com/bia-pain-bache)的[BPB-Worker-Panel](https://github.com/bia-pain-bache/BPB-Worker-Panel)的中文翻译版本

## 项目简介

本项目旨在为用户提供免费的、安全的、私有的 **VLESS**、**Trojan** 和 **Warp** 配置面板。即使域名或 Warp 服务被运营商封锁，也能保证连接畅通，支持两种部署方式：

- **Workers** 部署
- **Pages** 部署

🌟 如果你觉得 **BPB 面板** 有价值，欢迎捐赠支持本项目(向原作者捐赠) 🌟

### USDT (BEP20)

```text
0x111EFF917E7cf4b0BfC99Edffd8F1AbC2b23d158
```

## 功能特性

1. **免费且私有**：无需费用，服务器私有。
2. **直观面板**：界面简洁，配置与使用便捷。
3. **多协议支持**：提供 VLESS、Trojan 和 Wireguard (Warp) 协议。
4. **Warp Pro 配置**：针对特殊情况优化 Warp。
5. **Fragment 支持**：适用于复杂网络环境的碎片功能。
6. **全面路由规则**：自动绕过伊朗/中国/俄罗斯及局域网，屏蔽 QUIC、色情、广告、恶意软件、钓鱼及规避制裁。
7. **链式代理**：支持添加链式代理修正 IP。
8. **广泛客户端兼容**：支持 Xray、Sing-box、Clash-Mihomo 等主流客户端订阅。
9. **密码保护面板**：面板安全私密，支持密码保护。
10. **高度自定义**：支持自定义 IP 域名、代理 IP、DNS、端口、协议、Warp 端点等。

## 限制说明

1. **UDP 传输**：Workers 上的 VLESS 和 Trojan 协议不支持 **UDP**，默认禁用（影响如 Telegram 视频通话等），UDP DNS 也不支持。默认启用 DoH 增强安全性。
2. **请求限制**：每个 Worker 每天支持 10 万个请求，适合 2-3 个用户使用。你可以使用自定义个人域名绕过 VLESS/Trojan 的限制（Workers 部署）或选择无限制的 Warp 配置。

## 开始使用

1. **安装向导**：使用 [BPB 向导](httpss://github.com/zatursure/BPB-Wizard-Chinese) 进行安装。
2. **配置说明**：查看 [配置说明](https://bia-pain-bache.github.io/BPB-Worker-Panel/configuration/)。
3. **使用方法**：了解 [使用方法](https://bia-pain-bache.github.io/BPB-Worker-Panel/usage/)。
4. **常见问题**：查看 [常见问题](https://bia-pain-bache.github.io/BPB-Worker-Panel/faq/)。

## 支持的客户端

|       客户端        |       版本        |      Fragment      |      Warp Pro      |
| :-----------------: | :---------------: | :----------------: | :----------------: |
|     **v2rayNG**     | 1.10.2 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
|     **v2rayN**      | 7.12.5 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
|   **v2rayN-PRO**    |  1.9 或更高版本   | :heavy_check_mark: | :heavy_check_mark: |
|      **Husi**       |                   | :heavy_check_mark: |        :x:         |
|    **Sing-box**     | 1.12.0 或更高版本 | :heavy_check_mark: |        :x:         |
|    **Streisand**    | 1.6.48 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
|      **V2Box**      |                   |        :x:         |        :x:         |
|  **Shadowrocket**   |                   |        :x:         |        :x:         |
|     **Nekoray**     |                   | :heavy_check_mark: |        :x:         |
|     **Hiddify**     | 2.5.7 或更高版本  | :heavy_check_mark: | :heavy_check_mark: |
|     **MahsaNG**     |   13 或更高版本   | :heavy_check_mark: | :heavy_check_mark: |
|   **Clash Meta**    |                   |        :x:         |        :x:         |
| **Clash Verge Rev** |                   |        :x:         |        :x:         |
|     **FLClash**     |                   |        :x:         |        :x:         |
|   **AmneziaVPN**    |                   |        :x:         | :heavy_check_mark: |
|    **WG Tunnel**    |                   |        :x:         | :heavy_check_mark: |

## 环境变量

|    变量名    |              用途              |
| :----------: | :----------------------------: |
|   **UUID**   |           VLESS UUID           |
| **TR_PASS**  |          Trojan 密码           |
| **PROXY_IP** | 代理 IP 或域名 (VLESS, Trojan) |
| **SUB_PATH** |            订阅 URI            |
| **FALLBACK** |    回落域名 (VLESS, Trojan)    |
| **DOH_URL**  |            核心 DOH            |

---

## 随时间推移的 Stargazers 统计

[![Stargazers Over Time](https://starchart.cc/bia-pain-bache/BPB-Worker-Panel.svg?variant=adaptive)](https://starchart.cc/bia-pain-bache/BPB-Worker-Panel)

---

### 特别感谢

- 原作者 [bia-pain-bache](https://github.com/bia-pain-bache)
- VLESS, Trojan [Cloudflare-workers/pages proxy script](https://github.com/yonggekkk/Cloudflare-workers-pages-vless) 创建者 [yonggekkk](https://github.com/yonggekkk)
- CF-vless 代码作者 [3Kmfi6HP](https://github.com/3Kmfi6HP/EDtunnel)
- CF 优选 IP 程序作者 [badafans](https://github.com/badafans/Cloudflare-IP-SpeedTest), [XIU2](https://github.com/XIU2/CloudflareSpeedTest)
