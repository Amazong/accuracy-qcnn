|  Neural Net  | Top-1% 32/32 (W/A) | Top-1% 2≤W/A≤8 | Top-1% 1/1 (W/A) |
|:------------:|:------------------:|:--------------:|:----------------:|
|    AlexNet   |        [60.0](https://arxiv.org/abs/1605.07678)        |      [58.2](https://dl.acm.org/doi/abs/10.5555/3408352.3408572)     |       [57.0](https://arxiv.org/pdf/1807.07948.pdf)       |
| MobileNet-v2 |         [72](https://github.com/d-li14/mobilenetv2.pytorch)         |        —       |       [54.4](https://arxiv.org/pdf/1907.12629.pdf)       |
|   ResNet-18  |        [69.1](https://arxiv.org/abs/1605.07678)        |      [67.0†](https://arxiv.org/pdf/1707.09870.pdf)     |       [64.8](https://arxiv.org/pdf/1707.09870.pdf)       |
|     VGG16    |        [71.1](https://arxiv.org/abs/1605.07678)        |      [69.1](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Two-Step_Quantization_for_CVPR_2018_paper.pdf)      |       [68.9](https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/trit.2018.1026)       |
| Inception-v3 |         [78](https://arxiv.org/abs/1605.07678)         |      [76.4](https://github.com/Xilinx/graffitist)     |         —        |


‡ INT4 weights, INT8 activations, first/last layer weights are kept as INT8.
