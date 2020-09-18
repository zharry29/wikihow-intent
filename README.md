# Intent Detection with WikiHow
This repository contains pointers to data and models accompanying the paper "Intent Detection with WikiHow" by Li Zhang, Lyu Qing and Chris Callison-Burch.

The data and pre-trained HuggingFace models can be found [here](https://drive.google.com/drive/folders/1QbzEf-1yOz91lEonahVLf082zwuOJ4rj?usp=sharing).

| Model name  | Dataset trained on      | Model            |
|-------------|-------------------------|------------------|
| enwh_rl     | wikiHow-English         | RoBERTa-large    |
| enwh_xlmr   | wikiHow-English         | XLM-RoBERTa-base |
| eswh        | wikiHow-Spanish         | XLM-RoBERTa-base |
| thwh        | wikiHow-Thai            | XLM-RoBERTa-base |
| snips_wh_id | wikiHow-English + Snips | RoBERTa-large    |
| snips_id | Snips | RoBERTa-large    |
| sgd_wh_id | wikiHow-English + SGD | RoBERTa-large    |
| sgd_id | SGD | RoBERTa-large    |
| fb-en_wh_id_rl | wikiHow-English + Facebook-English | RoBERTa-large    |
| fb-en_id_rl | Facebook-English | RoBERTa-large    |
| fb-es_wh_id | wikiHow-Spanish + Facebook-Spanish | XLM-RoBERTa-base    |
| fb-es_enwh_id | wikiHow-English + Facebook-Spanish | XLM-RoBERTa-base    |
| fb-es_id | Facebook-Spanish | XLM-RoBERTa-base    |
| fb-th_wh_id | wikiHow-Thai + Facebook-Thai | XLM-RoBERTa-base    |
| fb-th_enwh_id | wikiHow-English + Facebook-Thai | XLM-RoBERTa-base    |
| fb-th_id | Facebook-Thai | XLM-RoBERTa-base    |

More information coming soon!

If you use our resources, please cite the following paper:
```
@misc{zhang2020intent,
    title={Intent Detection with WikiHow},
    author={Li Zhang and Qing Lyu and Chris Callison-Burch},
    year={2020},
    eprint={2009.05781},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```
