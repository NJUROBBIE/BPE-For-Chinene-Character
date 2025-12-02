# BPE-For-Chinene-Character
## 一、chat gpt4对词表单元组成的乱码的阅读结果
## 二、utf-8 ——> radical based code ——> token id
  基于minimind（https://github.com/jingyaogong/minimind/tree/master）的轻量化模型，在选择 one charactern one token的前提下，添加关联utf-8与radical的编码（不需要考虑所有的738个部首），最终实现。
