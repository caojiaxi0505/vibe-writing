# STEP2：构建 baseline 主结果表

目标：基于 Step1 调研结果，确定 benchmarks 与 baselines，并产出可直接用于论文的 LaTeX 主表。

## 必须项（MUST）

1. benchmarks 不少于 **5 个**，且需为 **2024-06-01** 之后提出（越新越优先）。
2. baselines 不少于 **6 个**，且均来源于 Step1 调研结果。
3. 所选 baselines 必须在上述 5 个 benchmarks 上已有公开结果（无需额外复现即可填表）。
4. 需访问 Hugging Face 趋势页确认主流基座模型：
   - `https://huggingface.co/models?pipeline_tag=text-generation&sort=trending`
5. 基座模型选择应满足在 **H200 × 2** 资源约束下可训练（需说明关键训练假设，如精度/批大小/序列长度）。
6. 输出 `STEP2/main_result_baseline.tex`，可直接用于论文展示。

## 建议项（SHOULD）

- 表格建议至少包含：模型、基座模型、benchmark、核心指标、训练预算、是否公开结果来源、引用。
- 指标命名与单位保持统一；必要时附注统计方式（如 mean±std）。

## 交付物（DELIVERABLES）

- `STEP2/main_result_baseline.tex`

## 注意事项

你不能对本文件进行任何修改，你只能对本文件进行阅读。
