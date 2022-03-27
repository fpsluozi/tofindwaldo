# To Find Waldo You Need Contextual Cues: Debiasing Who’s Waldo
This is the official repository for "To Find Waldo You Need Contextual Cues: Debiasing Who’s Waldo", ACL 2022. 
## Prerequisites
1. Follow the instructions from [the original Who's Waldo work](https://whoswaldo.github.io/) and acquire [the original dataset](https://whoswaldo.github.io/dataset) as well as [the source code](https://github.com/clairecyq/whos-waldo).
 
2. To generate the needed bottom-up image features, you may either use the original [repo](https://github.com/peteanderson80/bottom-up-attention) or the pytorch [re-implementation](https://github.com/MILVLG/bottom-up-attention.pytorch) up to your discretion.

3. In order to train/test with our splits, simply replace ```./dataset_meta/``` in the original source code repo with ours, and rerun the data preprocessing steps. We also provide a customizeable training config file ```config/train-whos-waldo-new-finetune.json``` for convenience.

## License
MIT

## Citation
In the works