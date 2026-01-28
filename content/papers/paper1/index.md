---
title: "Memorizing Long-tail Data Can Help Generalization Through Composition" 
date: 2026-01-26
tags: ["memorization","composition","long-tail data","deep learning theory"]
author: ["Mo Zhou*","Haoyang Ma*","Rong Ge"]
description: "This paper was accpeted to ICLR 2026." 
summary: "This paper shows that memorization of rare examples can meaningfully support generalization, both theoretically and empirically." 
# cover:
#     image: "paper1.png"
#     alt: "Some Uses For Olive Oil"
#     relative: true


---

---

##### Download

+ [Paper](https://arxiv.org/pdf/2510.16322)
<!-- + [Online appendix](appendix1.pdf) -->
<!-- + [Code and data](https://github.com/pmichaillat/feru) -->

---

##### Abstract

Deep learning has led researchers to rethink the relationship between memorization and generalization. In many settings, memorization does not hurt generalization due to implicit regularization and may help by memorizing long-tailed examples. In this paper, we consider the synergy between memorization and simple composition --- the ability to make correct prediction on a combination of long-tailed features. Theoretically, we show that for a linear setting, memorization together with composition can help the model make correct predictions on rare test examples that require a combination of long-tailed features, even if such combinations were never observed in the training data. Experiments on neural network architecture on simple data show that the theoretical insight extends beyond the linear setting, and we further observe that the composition capability of the model depends on its architecture.

---

<!-- ##### Figure 6: Some Uses For Olive Oil -->

<!-- ![](paper1.png) -->

---

##### Citation

Memorizing Long-tail Data Can Help Generalization Through Composition. ICLR 2026
Mo Zhou*, Haoyang Ma*, Rong Ge (* equal contribution)

```latex
@misc{zhou2025memorizinglongtaildatahelp,
      title={Memorizing Long-tail Data Can Help Generalization Through Composition}, 
      author={Mo Zhou and Haoyang Ma and Rong Ge},
      year={2025},
      eprint={2510.16322},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2510.16322}, 
}
```

---

<!-- ##### Related material

+ [Presentation slides](presentation1.pdf)
+ [Summary of the paper](https://www.penguinrandomhouse.com/books/110403/unusual-uses-for-olive-oil-by-alexander-mccall-smith/) -->