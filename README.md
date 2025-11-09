# 📚 Paper Reviews & Study Notes

Study-oriented paper reviews and summaries created during self-study and **Yonsei Artificial Intelligence Club (YAI)** sessions.  
Each review aims to analyze theoretical contributions and their relevance to **information-theoretic deep learning** and **efficient model design**.

---

## 🧩 Reviewed Papers

### 1. [Focal Self-Attention for Local-Global Interactions in Vision Transformers (Yang et al., 2021)](https://arxiv.org/abs/2107.00641)
- **Focus:** Efficient hierarchical attention that balances local and global dependencies.
- **Key Insight:** Introduces a *focal attention* mechanism combining fine-grained local attention with coarse global context aggregation.
- **Impact:** Improves computation–receptive field trade-offs, enabling scalability in large ViT backbones.
- **My Takeaway:** Demonstrates that attention sparsity can be framed as an *information bottleneck problem*, linking to ideas in quantization and efficient representations.
- 📄 [YAI Blog Review](https://yai-yonsei.tistory.com/50)

---

### 2. [Going Deeper with Convolutions (Szegedy et al., 2015)](https://arxiv.org/abs/1409.4842)
- **Focus:** Design and efficiency of the *Inception* architecture for deep convolutional networks.
- **Key Insight:** Introduces the *Inception module*, enabling multiple receptive fields within the same layer using parallel convolution paths.
- **Impact:** Achieves significant accuracy gains on ImageNet while maintaining computational efficiency — a pivotal moment in CNN evolution before residual networks.
- **My Takeaway:** The multi-branch design embodies the idea of *information diversification*, balancing expressivity and computational cost — a perspective later echoed in transformer multi-head architectures.
- 📄 [YAI Blog Review](https://yai-yonsei.tistory.com/34)

---

### 3. [To Be Added]
Planned future reviews:
- *Information Bottleneck Theory in Deep Learning* (Tishby, 2017)
- *Entropy-Constrained Quantization for Neural Compression* (Choi et al., 2022)

---

## 🧠 Purpose
This repository serves as an ongoing documentation of my effort to:
- Strengthen theoretical understanding of deep learning.
- Connect mathematical principles to practical model design.
- Build bridges between information theory, optimization, and network efficiency.
