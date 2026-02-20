# STEP2

根据step1的结果，选取baselines和benchmarks，构建baseline主表格；需要满足下面约束：

1. benchmarks应不少于5个，且需为2024年6月1日后提出的benchmark，越新越好（硬性要求）

2. baselines应不少于6个，来源于step1的调研结果，确保在5个benchmarks上都有已报告的结果，不需要我们进行复现才能得到相应结果（硬性要求）

3. baseline的基模不能太旧，你应该访问 “https://huggingface.co/models?pipeline_tag=text-generation&sort=trending” 以确认当前流行的基模，且基模可以在 H200 * 2 服务器上训练（硬性要求）

4. 应该形成一个能直接用于论文的LaTeX表格，保存在STEP2目录下，命名为main_result_baseline.tex，该表格应该全面，美观，这个表格将作为我们论文的主要结果与baselines对比展示（硬性要求）

# 注意事项

你不能对本文件进行任何修改，你只能对本文件进行阅读