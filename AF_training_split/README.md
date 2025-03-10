# Comparison with SOTAs using the training split of AF-SfMLearner

In this part, the training set file is consistent with [AF-SfMLearner](https://github.com/ShuweiShao/AF-SfMLearner/blob/main/splits/endovis/train_files.txt). If you intend to evaluate DVSMono with their setting, please directly use our provided [depth models](https://drive.google.com/drive/folders/1Nsz331v9jKbUHGfuCcrwzGK4QDbX8iWf?usp=sharing).

The comparison results are shown as follows:

| `Methods` | Abs Rel| Sq Rel| RMSE| RMSE log|  $\delta$ < 1.25  |
|-----------------------|----|----|----|------|--------|
| `Monodepth2` | 0.071  | 0.590  | 5.606  | 0.094  | 0.953  |
| `HR-Depth`| 0.063  | 0.493  | 5.271  | 0.087  | 0.963  |
| `DIFFNet`  | 0.061  | 0.477  | 5.084  | 0.084  | 0.966  |
| `Endo-SfMLearner` | 0.062  | 0.606  | 5.726  | 0.093  | 0.957  |
| `AF-SfMLearner`   | 0.059    | 0.435   | 4.925 | 0.082     | 0.974      |
| `MonoViT`| 0.064  | 0.513  | 5.418  | 0.088  | 0.967  |
| `Lite-Mono` | 0.063  | 0.490  | 5.197  | 0.087  | 0.962  |
| `DVSMono(Ours)` | **0.055** |**0.410**| **4.797**| **0.078**| **0.975**|