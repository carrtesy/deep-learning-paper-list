# Deep learning paper list

PIR: Papers I read

## Semi-supervised Learning

1. [Antti Tarvainen, Harri Valpola:
Mean teachers are better role models: Weight-averaged consistency targets improve semi-supervised deep learning results. NIPS 2017: 1195-1204](https://arxiv.org/abs/1703.01780) Method that averages model weights (exponential weighting) instead of label predictions. Compared to average of label prediction (temporal ensembling) which changes target only once per epoch, this can handle large dataset.
