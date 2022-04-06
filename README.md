# Deep learning paper list

PIR: Papers I read

## Time Series
1. [Taesung Kim, Jinhee Kim, Yunwon Tae, Cheonbok Park, Jang-Ho Choi, Jaegul Choo: Reversible Instance Normalization for Accurate Time-Series Forecasting against Distribution Shift](https://openreview.net/forum?id=cGDAkQo1C0p): Time series model suffer from distribution shift. To mitigate that problem, model without non-stationary features (mean, std).

## Semi-supervised Learning

1. [Antti Tarvainen, Harri Valpola:
Mean teachers are better role models: Weight-averaged consistency targets improve semi-supervised deep learning results. NIPS 2017: 1195-1204](https://arxiv.org/abs/1703.01780): Method that averages model weights (exponential weighting) instead of label predictions. Compared to average of label prediction (temporal ensembling) which changes target only once per epoch, this can handle large dataset.

## Curriculum Learning

1. [Petru Soviany, Radu Tudor Ionescu, Paolo Rota, Nicu Sebe:Curriculum Learning: A Survey. CoRR abs/2101.10382 (2021)](https://arxiv.org/abs/2101.10382): Survey paper (2021) of curriculum learning (CL). CL formulates learning scheme from easy to hard.
