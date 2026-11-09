# Aurora-Revival
Plasma 6 Global Theme

第一版已经制作完成！💙

Aurora Revival 0.1.0

构建成功

### 16 KB

ZIP 安装包 · Plasma 6 · Arch Linux

SVG、JSON 文件结构验证通过

安装与卸载脚本语法检查通过

原创 1920×1080 壁纸已包含

下载 ZIP 安装包

下载 Linux TAR.GZ 版本

### 1\. 已经包含的内容

| 组件                    | 状态  |
| --------------------- | --- |
| Plasma 6 Global Theme |     |
| Plasma Style          |     |
| Aurorae 4074 窗口装饰     |     |
| KDE 配色方案              |     |
| Kvantum               |     |
| 4074 风格壁纸             |     |
| 自动安装与卸载               |     |

注意：Kvantum 目前是配色和配置原型，还没有完成全部控件的 SVG 映射。完整 Sidebar、任务栏布局和图标包也留待后续版本。

### 2\. Arch Linux 安装

先解压 ZIP，然后打开终端：

```bash
cd Aurora-Revival-0.1.0

chmod +x install.sh
./install.sh
```

安装过程不需要 sudo，不会覆盖系统主题，也不会直接修改你的现有面板布局。

### 3\. 启用主题

安装后打开 KDE 系统设置：

* 颜色与主题 → 颜色 → Aurora Revival

* 颜色与主题 → Plasma 样式 → Aurora Revival

* 颜色与主题 → 窗口装饰 → Aurora 4074

* 桌面设置 → 壁纸 → AuroraRevival-4074.svg

Kvantum 原型暂时不建议作为日常 Qt 样式使用，等控件映射完善后再启用。

### 4\. 下一版开发目标

![Windows Longhorn/6.0.4074.idx02.040425-1535 - BetaArchive Wiki](https://images.openai.com/static-rsc-4/bNtkiFjkjFqsTI5nRLrAemCA_gmBekvlT-yybBFq8iHcbzOM8t1UbttxpKtQJuoZk7P_hdFNsV5kMbykNRzWG2UrejiDs4p_pY1HSYs84qDW-1_dWeewmE7Rkd54clSiUmB-nEQ95BjBgQx6dSAyV5QOuRST7sH9bdmifsbES_fz4xFvf8ZF-_XhkJWIEFIJ?purpose=fullsize)

v0.2 — Longhorn Sidebar

右侧透明侧边栏、时钟、系统信息、可拖动小组件。

![WinFuture Video: Longhorn Build 4074 mit DWM - WinFuture.de](https://images.openai.com/static-rsc-4/S_PKrWeBvqkGWMfN7Qqo3efekFiw2hwVwXgVoryoWpe6Ey82aMSRnJwCnb2hpWk188PyFB5S2jDP0SHuT1xljxBNfmbIDHcXRLi9tjX0J4MkF2HWbAa0OMnE2wqoMjp9Y-P49lsZInswGnQ1ogQ9ncwPfYDehxS3I97Wv3pjZhCJYpbXAs1Y8ySW8ggrZg79?purpose=fullsize)

v0.3 — Desktop Experience

4074 风格任务栏、开始菜单、窗口动画。

![Longhorn: Will Microsoft keep the door open?](https://images.openai.com/static-rsc-4/cdPxY_RneTmKR53VOsEP15TtrYrPtIxRCwSOrua3_OGpq0RZLKQK5qM_L_HMh63NIo3KtCWfDAgbI6ORPSVOiDB2b7wuvNOue2slN5aS2J5ORbvCjE3mivAiEzUf25ygpGaLAq_h3rOigCcpRdDrMmoIle8ys2017KzpN6DHFmOMx3W-izGUqLGyQ4u8JQo3?purpose=fullsize)

v0.4 — Complete Glass UI

完整 Kvantum 控件、Explorer 风格、图标和玻璃效果优化。

一个重要说明： 目前通过文件结构和脚本检查，还没有在真实 Plasma 6 会话中完成视觉及运行测试。建议先安装并反馈实际效果，我们再针对你的 Wayland 环境调整。

我很期待把它真正做成一个有完整 Longhorn 4074 灵魂的 KDE 桌面。✨
