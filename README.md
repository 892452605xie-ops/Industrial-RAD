# Industrial-RAD

Industrial-RAD 是工业场景下 Retrieval-Augmented Diffusion 相关论文与实验的项目仓库。仓库用于集中管理论文主文档、MPD 分章节材料、论文阅读记录、数据集说明、方法代码、实验记录和评估指标。

## 当前状态

- 仓库已初始化，主分支为 `main`。
- MPD Word 主文档已存放在 `docs/MPD/Master_Project_Document_MPD_v1.docx`。
- MPD 分章节 Markdown 草稿已建立在 `docs/MPD/`。
- 项目任务清单见 `TODO.md`，论文写作任务清单见 `docs/MPD/TODO.md`。

## 论文写作同步规则

以后所有与论文写作相关的新增、修改、重构或结论更新，都需要同步到以下位置：

1. `docs/MPD/Master_Project_Document_MPD_v1.docx`：论文主文档或主项目文档。
2. `docs/MPD/*.md`：对应章节的 Markdown 版本，便于 Git 追踪差异。
3. `docs/MPD/Decision_Log.md`：记录关键方向、方法、实验设计和写作结构决策。
4. `TODO.md` 或 `docs/MPD/TODO.md`：记录下一步任务和完成状态。

## 目录说明

```text
Industrial-RAD/
|-- README.md
|-- TODO.md
|-- LICENSE
|-- .gitignore
|-- docs/
|   |-- MPD/
|   |   |-- Master_Project_Document_MPD_v1.docx
|   |   |-- 00_Project_Brief.md
|   |   |-- 01_Background.md
|   |   |-- 02_Research_Gap.md
|   |   |-- 03_Literature_Review.md
|   |   |-- 04_Evidence_Chain.md
|   |   |-- 05_Distribution_Definition.md
|   |   |-- 06_Distribution_Metric.md
|   |   |-- 07_Method.md
|   |   |-- 08_Experiments.md
|   |   |-- Decision_Log.md
|   |   `-- TODO.md
|   `-- Papers/
|-- datasets/
|-- retrieval/
|-- diffusion/
|-- experiments/
|-- metrics/
|-- detector/
`-- scripts/
```

## 工作流

1. 写作前先查看 `TODO.md` 和 `docs/MPD/TODO.md`。
2. 修改论文内容时，同时更新 Word 文档和对应 Markdown 章节。
3. 有重要判断时，追加到 `docs/MPD/Decision_Log.md`。
4. 完成阶段性工作后提交 Git，并推送到 GitHub。

## GitHub 远端

远端仓库地址：

```text
https://github.com/892452605xie-ops/Industrial-RAD.git
```
