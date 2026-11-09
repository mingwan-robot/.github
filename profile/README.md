# 明湾学校 2 号楼 · 人机共生情景模拟器
**Mingwan Building 2 · Human–Robot Cohabitation Simulator**

G5 课程用情景模拟网站：选楼层 / 时段 / 机器人组合，观察人流与机器人如何共用通道、哪里产生冲突，并比较「现状 A」与「提案 B」。

## 👉 学生入口 / Student access

**https://mingwan-robot.github.io/cohab/**

手机、电脑浏览器直接打开即可，无需安装、无需登录。第一次打开会弹出 3 步引导。

| 用途 / Purpose | 链接 / Link |
|---|---|
| 普通练习 / Normal | https://mingwan-robot.github.io/cohab/ |
| 机房只读模式 / Read-only | https://mingwan-robot.github.io/cohab/#ro=1 |
| 打开即播放一整天 / Autoplay | https://mingwan-robot.github.io/cohab/#play=1 |
| 直接看 2F·午餐·提案对比 / Deep link | https://mingwan-robot.github.io/cohab/#floor=2F&slot=T5&variant=B&view=compare |

备用地址 / Backups：<https://captainlisland-cloud.github.io/mingwan-robot/> · <https://captainlisland-cloud.github.io/>

## 三步使用 / Three steps

1. **选时段 / Pick a slot** — 顶栏 T1–T8（T5 午餐最挤），或点底部播放。
2. **看冲突 / Inspect conflicts** — 点图上 ①②③，右栏给出类型、严重度、原因与 3 条改进建议；点机器人看路线，点门看通行判定。
3. **比方案 / Compare** — 切「现状 A / 提案 B」，或点「对比」看双地图 + 3 个指标 + Δ。

键盘：`1`/`2` 切楼层 · `空格` 播放 · `←`/`→` 步进 · `Esc` 取消选择。

## 数据说明 / Data notes

- **V1 为离线情景模拟器**：所有位置、人数、时长均为模拟假设值，不接真实机器人、不实时定位、不下发控制。
- 底图来自 `Y1 to Y3 Floor Plan 20260821.pptx` 中 Building 2 的 1F / 2F CAD 导出；门净宽不可辨，全标「待确认」；比例与指北待校准。
- **机器人路线为示意**：已按「尽量避开墙体」重算，但 PRD §10.1 的走廊中心线路网尚未建立，不能当作真实可通行路径引用。
- 「编辑」模式可拖动对象、改属性、增删，并导出 / 导入 JSON；改动仅存本机 localStorage。

## 仓库 / Repositories

- [`cohab`](https://github.com/mingwan-robot/cohab) — 站点本体（纯静态，GitHub Pages: `main` / root）
- [`.github`](https://github.com/mingwan-robot/.github) — 本组织主页说明

---
*G5 · Standard Lesson Planning · 2026*
