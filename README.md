# DA-CLIP: DA-CLIP: Mitigating Granularity Mismatch in Zero-Shot Anomaly Detection via Decoupled Text-Visual Alignment

<!-- 这里的标签可以根据需要保留或删除 -->
[Submitted to CVPR2026] 
[Official Pytorch Implementation of Mitigating Granularity Mismatch in Zero-Shot Anomaly Detection via Decoupled Text-Visual Alignment, 2025]

<!-- 放置一张最能代表你项目的流程图或效果图 -->
![Teaser](figures/teaser.png)
*Figure 1: [图片的简短描述，例如：The overall architecture of our proposed method, illustrating the transition from global PCA features to local similarity refinement.]*

## Abstract

<!-- 这里写你的摘要，可以参考 AA-CLIP 的写法：提出背景 -> 现有问题 -> 你的解决方法 -> 效果 -->
[背景] Visual representation learning is critical for downstream tasks like anomaly detection and classification. 
[问题] However, existing methods often struggle with [描述你解决的问题，例如：distinguishing subtle inter-class differences]. 
[方法] To address this, we propose **[你的模型名称]**, which enhances feature extraction by [简述你的核心创新点]. 
[效果] Extensive experiments demonstrate that our approach achieves state-of-the-art performance on [数据集名称] benchmarks, effectively improving both visual separability and semantic consistency.

## Results

<!-- 展示你的实验结果，特别是可视化结果 -->
### Visualizations
We provide comprehensive analysis using both **PCA visualization** and **Similarity Maps** to validate the effectiveness of our representations.

![Results](figures/results.png)
*Figure 2: (Left) t-SNE/PCA visualization showing clear separation between classes. (Right) Similarity maps demonstrating high intra-class compactness.*

## Quick Start

### 1. Installation

```bash
# Clone the repository
git clone https://github.com/[你的Github用户名]/[你的仓库名].git
cd [你的仓库名]

# Create a conda environment
conda create -n [环境名称] python=3.10 -y
conda activate [环境名称]

# Install dependencies
pip install -r requirements.txt
