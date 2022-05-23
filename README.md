# To Find Waldo You Need Contextual Cues: Debiasing Who’s Waldo
This is the official repository for ["To Find Waldo You Need Contextual Cues: Debiasing Who’s Waldo"](https://aclanthology.org/2022.acl-short.39/). 

* [Yiran Luo](https://github.com/fpsluozi), [Pratyay Banerjee](https://pratyay-banerjee.github.io/), [Tejas Gokhale](https://www.public.asu.edu/~tgokhale/), [Yezhou Yang](https://yezhouyang.engineering.asu.edu/), [Chitta Baral](https://www.public.asu.edu/~cbaral/) .
* ACL 2022 (Short Paper)
## Prerequisites
1. Follow the instructions from [the original Who's Waldo work](https://whoswaldo.github.io/) and acquire [the original dataset](https://whoswaldo.github.io/dataset) as well as [the source code](https://github.com/clairecyq/whos-waldo).
 
2. To generate the needed bottom-up image features, you may either use the original [repo](https://github.com/peteanderson80/bottom-up-attention) or the pytorch [re-implementation](https://github.com/MILVLG/bottom-up-attention.pytorch) up to your discretion.

3. In order to train/test with our splits, simply replace ```./dataset_meta/``` in the original source code repo with ours, and rerun the data preprocessing steps. We also provide a customizeable training config file ```config/train-whos-waldo-new-finetune.json``` for convenience.

## License
MIT

## Citation
```
@inproceedings{luo-etal-2022-find,
    title = "To Find Waldo You Need Contextual Cues: Debiasing Who{'}s Waldo",
    author = "Luo, Yiran and Banerjee, Pratyay and Gokhale, Tejas and Yang, Yezhou and Baral, Chitta",
    booktitle = "Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers)",
    month = may,
    year = "2022",
    url = "https://aclanthology.org/2022.acl-short.39",
    pages = "355--361",
}
```
