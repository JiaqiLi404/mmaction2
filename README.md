# 🎬 MMAction2 (Enhanced Fork)

[![License](https://img.shields.io/badge/license-Apache--2.0-green)](LICENSE)

**Enhanced fork of [MMACTION2](https://github.com/open-mmlab/mmaction2) with full support for:**

- ✅ **NumPy 2.0+**
- ✅ **Transformers 4.45+**

---

## 🔥 Why this fork?

The original MMACTION2 is an excellent video understanding toolbox.  
However, it has **compatibility issues with recent versions of NumPy and Transformers**, which limits integration with modern pipelines.  

This fork solves that:

- Fixes `np.sctypes` deprecation in NumPy 2.0+
- Updates deprecated imports and APIs for Transformers 4.45+
- Maintains all original MMACTION2 functionalities

---

## ⚡ Installation

```bash
# Clone this fork
git clone https://github.com/JiaqiLi404/mmaction2.git
cd mmaction2

pip install  .
```

---

## 🤝 Community Collaboration

If you encounter **any issues, incompatibilities, or ideas for improvement**, we welcome the community to collaborate and help improve compatibility further!