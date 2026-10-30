# 🚀 LoadPulse - 轻量级极客风 API 性能压测工具

LoadPulse 是一款基于 Python (FastAPI) 与 Vue3 开发的轻量级、免环境配置的 API 性能测试工具。专为内网接口调试、性能瓶颈排查及 CI/CD 自动化测试设计。

<img width="2848" height="1628" alt="图片" src="https://github.com/user-attachments/assets/ff3e28f7-7610-447f-aea2-17ec6b2b67d8" />

## ✨ 核心特性 (Core Features)

*   **🛡️ 智能断言 (Smart Assertions)**：支持 JSONPath 解析（如 `$.code = 200`），彻底拒绝“只看 HTTP 200”的假压测。
*   **📊 大厂级指标 (P99 Analytics)**：告别被平均值欺骗，内置 P50/P90/P95/P99 及最大耗时统计，长尾延迟一目了然。
*   **🔔 自动化告警 (Webhook Alerts)**：压测结束后自动分析结果，若成功率或 P99 达标不合格，自动推送钉钉/企微告警。
*   **📁 CSV 参数化 (Data Parameterization)**：支持循环、唯一、随机模式，轻松模拟大量真实用户并发。
*   **🌐 分布式压测 (Distributed Testing)**：支持多节点 Worker 联合施压，突破单机瓶颈。
*   **📄 纯离线报告 (Offline Reports)**：一键导出单文件 HTML 报告，内联所有图表与数据，断网也能看。

## 🖥️ 界面预览 (Screenshots)

<img width="2534" height="2912" alt="图片" src="https://github.com/user-attachments/assets/83ca1f97-a7d4-46fd-af71-7fc7505084ac" />
<img width="1464" height="908" alt="图片" src="https://github.com/user-attachments/assets/75ec996d-a831-4d83-a09b-e9e7ff23b0c8" />

## 📦 下载与安装 (Download)

无需配置任何 Python 环境，开箱即用。请在右侧的 **[Releases](../../releases)** 页面下载最新版本：

*   macOS 用户：下载 `LoadPulse_Mac_v2.0.zip`
*   Windows 用户：下载 `LoadPulse_Win_v2.0.zip`

> **⚠️ 免费版限制**：免费版限制 10 并发 / 100 总请求数，且不支持导出报告与智能断言。如需解锁全部 PRO 功能（无限并发、Webhook、离线报告），请联系作者获取商业授权。

## 🛠️ 技术栈 (Tech Stack)

*   **Engine**: Python 3.10, FastAPI, Uvicorn, httpx, asyncio
*   **Frontend**: Vue 3, TailwindCSS, ECharts
*   **Desktop**: PyWebview
*   **Packaging**: PyInstaller, PyArmor

---
*Developed by [你的 GitHub 用户名]*# LoadPulse
A lightweight API performance testing tool with intelligent assertions.
