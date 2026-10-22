### Hi, I'm YuHou 👋

Windows 音频 / DSP 方向，专注**用户态、零内核驱动**的实时音频处理。

---

#### 🔧 主要项目

**[DRC 虚拟声卡](https://github.com/surge-me/drc-virtual-soundcard)** — 枪声不炸耳、脚步听得见

Windows 系统级音频动态范围控制器：虚拟线捕获 → 实时 DSP（lookahead 限幅 + 弱声上抬 + 10 段 EQ）→ 真实输出设备，配 WPF 托盘 GUI、全局热键与实时电平曲线。

`C++` `C#` `WPF` `WASAPI` `DSP` · 零内核驱动 · 零系统文件修改 · 不注入游戏进程 · MIT

[![release](https://img.shields.io/github/v/release/surge-me/drc-virtual-soundcard?label=release)](https://github.com/surge-me/drc-virtual-soundcard/releases/latest)
[![license](https://img.shields.io/badge/license-MIT-green)](https://github.com/surge-me/drc-virtual-soundcard/blob/main/LICENSE)
[![tests](https://img.shields.io/badge/ctest-13%2F13%20passing-success)](https://github.com/surge-me/drc-virtual-soundcard)

---

#### 关注方向

- **实时音频 DSP**：限幅、动态范围压缩、图形 EQ、参数平滑
- **Windows 音频栈**：WASAPI 共享/独占模式、端点热插拔、APO
- **无锁 IPC**：seqlock 共享内存参数热更新
- **工程质量**：golden vectors、变异测试、可复现构建

---

<sub>📫 通过 [仓库 Issues](https://github.com/surge-me/drc-virtual-soundcard/issues) 联系我</sub>
