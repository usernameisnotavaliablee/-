# 淳阳 2026 招新海报 - Grill-Me 拷问记录

> 任务：达达主义 x 粗野主义招新海报，网页形式交付，比例 4:3（方向待确认）。
> 素材：往期图 x2、达达/粗野/包豪斯/野兽参考图、淳阳小太阳.png（透明底）、大致要求.md。
> 约束：不读取目录内其他 Agent 产出的 HTML。

## 已定
- （待填）

## 拷问中
- Q1 画面方向：竖版 3:4 / 横版 4:3 / 主竖版+横版变体 —— 待回答

## 排队问题
- Q2 风格配比：达达拼贴为主 / 粗野网格为主 / 外粗野内达达
- Q3 小太阳：直接贴纸 / 黑白半调颠覆 / 蜡笔+几何双版本
- Q4 二维码：生成 example.com 实物 / 手写占位框
- Q5 网页形态：静态海报页 / 印刷模式切换 / 轻动效
- Q6 文案权限：严格按文档 / 可加少量达达式碎文案
- Q7 用途：屏幕传播 / 打印 / 两者兼顾

## 技术侦察（已确认）
- 小太阳 PNG/WebP 均带透明通道，可直接当贴纸
- ImageMagick 可用；无本地 QR 库，真码走 qrserver API 生成（需联网批准）
- 字体：PingFang SC / Hiragino Sans GB W6（中文重字）、DIN Condensed Bold、Avenir Next Condensed、Impact、Arial Black、MarkerFelt / Noteworthy（手写）
- Playwright 无头截图验证可行（Edge executablePath）
