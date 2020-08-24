# 中文生成式预训练模型

NLU的预训练模型大家应该见过不少了，NLG的预训练资源还比较少。这里汇总一些中文的生成式预训练模型，给出bert4keras下的加载方式。

## GPT

以GPT为代表的单向语言模型预训练。

### GPT Base（NEZHE-GEN）

- **链接**：https://github.com/huawei-noah/Pretrained-Language-Model/tree/master/NEZHA-Gen-TensorFlow
- **大小**：1亿参数，体积390M
- **说明**：结构跟BERT Base一致，通用语料训练，官方github提供了下载链接，不过保存了多余的meta导致权重过大，笔者对原始权重进行了转换，可以从笔者提供的链接下载，结果跟原版一样。
- **使用**：[basic_language_model_nezha_gen_gpt.py](https://github.com/bojone/bert4keras/blob/master/examples/basic_language_model_nezha_gen_gpt.py)

### GPT2-ML

- **链接**：https://github.com/imcaspar/gpt2-ml
- **大小**：15亿参数，体积5.3G
- **说明**：基于BERT代码修改，跟最大的英文版GPT2大小一致，通用语料训练，目前开放了两个版本，详情请查看项目说明。
- **使用**：[basic_language_model_gpt2_ml.py](https://github.com/bojone/bert4keras/blob/master/examples/basic_language_model_gpt2_ml.py)

## 交流

QQ交流群：67729435，微信群请加机器人微信号spaces_ac_cn
