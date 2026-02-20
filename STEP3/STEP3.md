# STEP3

发挥想象力，提出一个“逻辑上非常make sense，但没人探索过”的新方法，你需要注意：

1. STEP3为论文最关键的部分methodology章节提供依据，你应该确保这个idea在逻辑上是说得通的，且是目前没有人做过的，即确保idea的创新性（硬性要求）

2. idea应该尽可能充实，且能够使用尽可能多且复杂的数学公式进行推导，这是ICML/NeurIPS/ICLR这类顶会的风格偏好，注意数学符号需要保证前后一致且互不冲突（硬性要求）

3. idea需要拆解为3个contribution，这意味着你需要在method章节中包含3个subsection，且注意，每个subsection中都要包含足够的数学推导（硬性要求）

4. methodology章节不能涉及到任何的实验设计，尽可能抽象地描述idea（硬性要求）

5. 撰写methodology章节，符合ICML/NeurIPS/ICLR风格，保存在STEP3目录下，命名为method.tex，结构按照下面的格式：

    - 首先是对论文方法的概述，你可以参考下面的例子（该例子是另一个领域的NeurIPS spotlight，你只需参考长度和风格）：In this section, we present Voxel Mamba, a group-free Voxel State Space Model-based 3D backbone that can be applied to most voxel-based 3D detectors. We first introduce the preliminary concepts associated with our method, followed by the overall architecture of Voxel Mamba. Then, we describe in detail the fundamental components of Voxel Mamba, including the Hilbert Input Layer (HIL), Dual-scale SSM Block (DSB), and Implicit Window Partition (IWP).

    - 然后是Preliminaries以及Overall Architecture，各自使用一个subsection

    - 之后是三个subsection，对应拆解的三个contribution

    - 注意methodology章节需要有一个伪代码块

# 注意事项

你不能对本文件进行任何修改，你只能对本文件进行阅读