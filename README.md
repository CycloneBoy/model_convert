# model convert
> convert some model to pytorch

## Chinese-MobileBERT
> convert tensorflow checkpoint to pytorch.
> origin checkpoint from https://github.com/ymcui/Chinese-MobileBERT

### model card

### Huggingface-Transformers

With [Huggingface-Transformers](https://github.com/huggingface/transformers), the models above could be easily accessed and loaded through the following codes.
```
tokenizer = MobileBertTokenizer.from_pretrained("MODEL_NAME")
model = MobileBertModel.from_pretrained("MODEL_NAME")
```
**Notice: Please use BertTokenizer and BertModel for loading these model. DO NOT use RobertaTokenizer/RobertaModel!**

The actual model and its `MODEL_NAME` are listed below.

| Original Model | MODEL_NAME |
| - | - |
| Chinese-MobileBERT-base-f2 | cycloneboy/chinese_mobilebert_base_f2 |
| Chinese-MobileBERT-base-f4 | cycloneboy/chinese_mobilebert_base_f4 |
| Chinese-MobileBERT-large-f2 | cycloneboy/chinese_mobilebert_large_f2 |
| Chinese-MobileBERT-large-f4 | cycloneboy/chinese_mobilebert_large_f4 |


## refer to

- [Chinese-MobileBERT](https://github.com/ymcui/Chinese-MobileBERT)