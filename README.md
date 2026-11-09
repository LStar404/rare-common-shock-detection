# 稀有共同冲击的二元快照检测

英文题名：*Rare Common-Shock Detection from Binary Snapshots — Minimum Cover Order and Optimal Inspection*。

这是“随机覆盖问题”研究的第063轮英文讨论稿。模型允许独立冲击同时覆盖若干块。每次实验独立重启，只在选定时刻记录一次完整二元快照。比较两种全局冲击率时，通过调整专属率保持单块边缘相同。论文研究最低覆盖阶如何决定两候选的 Hellinger 分离与最佳观测时间，并给出二阶边界和两种重叠几何的对比。

## 阅读与编译

- [英文论文 PDF](rare-common-shock-detection.pdf)
- [LaTeX 源文件](rare-common-shock-detection.tex) · [可编译源码包](latex-source.zip) · [编译说明](BUILD.md)
- [固定维 Hellinger 剖面](fixed-dimension-profile.png) · [增长维重叠几何对比](growing-overlap-comparison.png)

解压源码包并在其目录执行 `latexmk -pdf rare-common-shock-detection.tex` 或 `tectonic rare-common-shock-detection.tex`。参考文献已包含在主文件中，两幅图需与主文件置于同一目录。

## 第063轮冻结版

| 项目 | 记录 |
| --- | --- |
| Git 标签 | [`round-063-2026-11-09`](https://github.com/LStar404/rare-common-shock-detection/releases/tag/round-063-2026-11-09) |
| 原始交付提交 | [`cc978885c3a296adbc6c6f54b5c668c1250cc775`](https://github.com/LStar404/rare-common-shock-detection/commit/cc978885c3a296adbc6c6f54b5c668c1250cc775) |
| 原始交付时间 | `2026-11-09 21:51:32 +08:00`（`2026-11-09T13:51:32Z`） |
| GitHub 冻结版发布时间 | `2026-11-09 21:55:38 +08:00`（`2026-11-09T13:55:38Z`） |

引用这一稿时，可用标签和提交号定位原始文件。该版本是研究讨论稿，定理范围与证明以正文为准。
