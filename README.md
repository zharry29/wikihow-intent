# Intent Detection with WikiHow
This repository contains pointers to data and models accompanying the paper "Intent Detection with WikiHow" by Li Zhang, Lyu Qing and Chris Callison-Burch.

The data and pre-trained model binaries can be found [here](https://drive.google.com/drive/folders/1w3G7ZqdiskORLl_9pUjE_AXfUMh1-NqJ?usp=sharing). The provided iPython Notebook demonstrates how to load and use our pretrained models. It is recommended that you run the notebook using Google Colab to avoid dependency issues.

All our models are implemented using [HuggingFace Transformers](https://github.com/huggingface/transformers) and are hosted on its model hub. You can find the models [here](https://huggingface.co/zharry29). To find hyperparameters, open the link, click on the model name, click on "List all files in model", and then load `training_args.bin` using PyTorch. To use our pretrained models, simply install the library (and its dependencies) and import our models. The model namings are as follows:

| Model name  | Dataset trained on      | Model            |
|-------------|-------------------------|------------------|
| intent_enwh_rl     | wikiHow-English         | RoBERTa-large    |
| intent_enwh_xlmr   | wikiHow-English         | XLM-RoBERTa-base |
| intent_eswh        | wikiHow-Spanish         | XLM-RoBERTa-base |
| intent_thwh        | wikiHow-Thai            | XLM-RoBERTa-base |
| intent_snips_wh_id | wikiHow-English + Snips | RoBERTa-large    |
| intent_snips_id | Snips | RoBERTa-large    |
| intent_sgd_wh_id | wikiHow-English + SGD | RoBERTa-large    |
| intent_sgd_id | SGD | RoBERTa-large    |
| intent_fb-en_wh_id_rl | wikiHow-English + Facebook-English | RoBERTa-large    |
| intent_fb-en_id_rl | Facebook-English | RoBERTa-large    |
| intent_fb-es_wh_id | wikiHow-Spanish + Facebook-Spanish | XLM-RoBERTa-base    |
| intent_fb-es_enwh_id | wikiHow-English + Facebook-Spanish | XLM-RoBERTa-base    |
| intent_fb-es_id | Facebook-Spanish | XLM-RoBERTa-base    |
| intent_fb-th_wh_id | wikiHow-Thai + Facebook-Thai | XLM-RoBERTa-base    |
| intent_fb-th_enwh_id | wikiHow-English + Facebook-Thai | XLM-RoBERTa-base    |
| intent_fb-th_id | Facebook-Thai | XLM-RoBERTa-base    |

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
