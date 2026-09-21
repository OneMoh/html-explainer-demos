# html-explainer-demos

[html-explainer](https://github.com/OneMoh/html-explainer) 的成片演示素材。

三条视频全部由 html-explainer 流水线生成，未做手工后期——画面（HTML/CSS/GSAP）、
配音（edge-tts）、硬字幕、封面，都是流水线的产物。

| # | 演示 | 时长 | 视频 | 封面 |
|---|------|------|------|------|
| 01 | AI 时代不买课，我自己做条视频（技能介绍：23 种画面风格） | 2:46 | [mp4](videos/01-ai-era-self-made-video.mp4) | [png](covers/01-ai-era-self-made-video.png) |
| 02 | 港股创新药早盘涨超 5%（NYT 编辑级数据图表） | 2:06 | [mp4](videos/02-hk-innovative-drug-early-session.mp4) | [png](covers/02-hk-innovative-drug-early-session.png) |
| 03 | 炒股的公司顺手造出了大模型（量化简史） | 1:27 | [mp4](videos/03-quant-company-built-an-llm.mp4) | [png](covers/03-quant-company-built-an-llm.png) |

主仓库的 README 通过本仓库的媒体直链引用这些视频，因此：

- `git clone` **主仓库**不会拉到任何视频（视频只住在这里）；
- `package_skill.py` 打出的 zip 也不含视频（打包规则排除 `*.mp4`）。

封面为 `cover_169.png`（1920×1080），由流水线的封面双方案产出。
