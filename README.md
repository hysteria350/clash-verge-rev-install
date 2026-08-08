# Clash Verge Rev Windows 使用教程：下载安装、配置订阅与代理设置指南

Clash Verge Rev 是一款跨平台的图形化代理客户端，基于 Mihomo 内核开发，支持 Windows、macOS 和 Linux 操作系统。它继承了 Clash 的高性能和灵活性，支持多种代理协议，如 Shadowsocks、VMess、Trojan、Tuic、Hysteria 等，兼容各类机场订阅。Clash Verge rev 提供现代化的用户界面，配置方式友好，支持多语言、自动订阅更新、节点筛选、分流规则管理等功能。得益于 Mihomo 内核的增强，Clash Verge rev 支持更丰富的协议特性与策略组配置，是高级用户与跨境办公场景中的优选工具。本文在 Windows 上讲述如何安装和使用 Clash Verge Rev。

*   [Clash verge 官网](https://www.clashverge.dev/)
    
*   [Clash verge Github](https://github.com/clash-verge-rev/clash-verge-rev)
    
*   [TG 频道: @clash\_verge\_rev](https://t.me/clash_verge_rev)
    

## 1\. **界面预览**[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#1 "Permanent link")

![Clash Verge Rev](https://proxyguide.github.io/images/clash-verge-rev/preview_light.png)

_Clash Verge Rev 界面预览_

## 2\. **下载与安装**[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#2 "Permanent link")

### 2.1. 官网地址[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#21 "Permanent link")

**Clash Verge Rev 官网**下载地址：[https://github.com/clash-verge-rev/clash-verge-rev/releases](https://github.com/clash-verge-rev/clash-verge-rev/releases) 新手使用建议下载稳定版本，即版本号后标记为 `Latest` 的版本。

### 2.2. 如何选择版本？[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#22 "Permanent link")

在官网下载地址中，有众多版本可供下载，如下表所示，其中文件名当中的数字为版本号，版本号之后跟着的是平台名称及安装包类型。

| **package** | **description** |
| --- | --- |
| [Clash Verge\_2.5.2\_x64-setup.exe](https://github.tbap.top/https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_x64-setup.exe) | Windows 64位安装包（Intel/AMD CPU，标准安装版） |
| [Clash Verge\_2.5.2\_x64\_fixed\_webview2-setup.exe](https://github.tbap.top/https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_x64_fixed_webview2-setup.exe) | Windows 64位安装包（内置修复版 WebView2，适用于系统缺少 WebView2 环境） |
| [Clash Verge\_2.5.2\_arm64-setup.exe](https://github.tbap.top/https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_arm64-setup.exe) | Windows ARM64 安装包（ARM Windows设备） |
| [Clash Verge\_2.5.2\_arm64\_fixed\_webview2-setup.exe](https://github.tbap.top/https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_arm64_fixed_webview2-setup.exe) | Windows ARM64 安装包（ARM Windows设备，内置修复版 WebView2，适用于系统缺少 WebView2 环境） |

### 2.3. Windows 上如何安装 Clash Verge Rev？[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#23-windows-clash-verge-rev "Permanent link")

在本文中我们使用 [Clash.Verge\_2.5.2\_x64-setup.exe](https://github.tbap.top/https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_x64-setup.exe) 安装包进行安装。

软件的安装教程和一般安软件没什么不同，一般按照默认的选项直接安装即可，在第一次打开安装包的时候，会提示 `Windows 已保护你的电脑`，只需要点击`更多信息`，然后在点击`仍要运行`就可以，如下图所示，接下来的步骤和安装一般的软件没有区别。

[![Microsoft Defender SmartScreen](https://proxyguide.github.io/images/clash/1730617327-Microsoft-Defender-SmartScreen-01.jpg)](https://proxyguide.github.io/images/clash/1730617327-Microsoft-Defender-SmartScreen-01.jpg)

点击更多信息

点击仍要运行，然后安装安装向导进行安装。

## 3\. 导入订阅[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#3 "Permanent link")

先进行 [订阅购买](https://docs.proxyguide.org/recommen/v2ray_node_recommendations/) ，获取到订阅链接。订阅链接位于：仪表盘 > 一键订阅 , 然后复制订阅地址或者扫描二维码订阅。

[![导入订阅](https://proxyguide.github.io/images/clash/remote_url.C_pIdA2k.gif)](https://proxyguide.github.io/images/clash/remote_url.C_pIdA2k.gif)

## 4\. 配置[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#4 "Permanent link")

开启系统代理，开启系统代理以后就不用为某个或某些应用配置代理。

[![enable system proxy](https://proxyguide.github.io/images/clash/clash-verge-system-proxy.png)](https://proxyguide.github.io/images/clash/clash-verge-system-proxy.png)

现在浏览器可以打开 [google.com](https://www.google.com/) 了。

> 系统代理：（原理：通过上方开关自动修改操作系统的代理设置）能处理大部分通过浏览器的科学上网需求。
> 
> Tun 模式：(使用前请确保你已阅读相关教程)在系统中安装虚拟网卡，以接管不支持“系统代理”的程序（例如游戏和命令行）。

## 5\. 如何彻底卸载 Clash-verge[¶](https://docs.proxyguide.org/clash/clash-verge-rev-on-windows/#5-clash-verge "Permanent link")

1.  Windows 下卸载删除 service 的方法
    
    *   方法 1：在软件设置菜单，虚拟网卡旁边点删除图标
        
    *   方法 2：手动删除：打开软件安装目录，进入 resource 文件夹，使用 cmd 运行 uninstall-service.exe
        
2.  相关文件及目录
    

| **文件类型** | **路径** | **说明** |
| --- | --- | --- |
| **WebView 缓存目录** | `C:\Users\你的用户名\AppData\Local\io.github.clash-verge-rev.clash-verge-rev` | ⚠️ 强烈建议每次升级后清空此目录 |
| **窗口状态文件** | `C:\Users\你的用户名\AppData\Roaming\io.github.clash-verge-rev.clash-verge-rev\.window-state.json` | 记录窗口大小位置等，窗口出问题请删除此文件 |
| **Clash Verge 配置文件** | `C:\Users\你的用户名\AppData\Roaming\io.github.clash-verge-rev.clash-verge-rev\verge.yaml` | 主配置文件 |
| **配置(软件工作)目录** | `C:\Users\你的用户名\AppData\Roaming\io.github.clash-verge-rev.clash-verge-rev\` | 软件工作目录 |
| **订阅(配置)文件目录** | `C:\Users\你的用户名\AppData\Roaming\io.github.clash-verge-rev.clash-verge-rev\profiles\` | 存放订阅配置文件 |
