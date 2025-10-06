# VisionDES: Deep Dynamic Ensemble Selection for Trustworthy Image Classification 

[![My Skills](https://skillicons.dev/icons?i=python,pytorch)](https://skillicons.dev)  


![Alt text](https://github.com/Adversarial-Panda/vision_des/blob/main/images/framework_visiondes.png)


### Hyperparameters of VisionDES

| **Parameter** | **Description** | **Default** |
|----------------|-----------------|--------------|
| `pool_classifiers` | List of classifiers | `None` |
| `k` | Number of neighbors in RoC | `7` |
| `return_logits` | Whether to return raw logits instead of just prediction | `False` |
| `explain` | Enable explanation mechanism | `False` |
| `top` | Select only top n classifiers | `False` |
| `n` | Number of top classifiers to select | `3` |
| `FIRE` | Use FIRE-based filtering mechanism | `False` |
| `Per-class minimum` | Min number of classifiers per class in selection (FIRE) | `1` |
| `similarity` | Enable similarity-based weighting in aggregation | `True` |
| `similarity_threshold` | Minimum similarity for including a selected ensemble | `0` |
| `alpha` | Weighting factor for combining competence and similarity | `0.6` |
| `knorae` | Use KNORA-E instead of default KNORA-U for selection | `False` |

