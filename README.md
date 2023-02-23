# t5-japanese
日本語T5モデル

## 日本語T5事前学習済みモデル

https://huggingface.co/sonoisa/t5-base-japanese


## sonoisa様の解説記事

https://qiita.com/sonoisa/items/a9af64ff641f0bbfed44

## 修正に関する記事

方言翻訳機制作大作戦 その1.99 - Qiita https://qiita.com/Bandolu/items/b7423cfd7fd32b618440


## 転移学習の例

- [ニュース記事のジャンル予想（文章分類）](https://colab.research.google.com/github/sonoisa/t5-japanese/blob/main/t5_japanese_classification.ipynb)
- [ニュース記事のタイトル生成（一種の文章要約）](https://colab.research.google.com/github/sonoisa/t5-japanese/blob/main/t5_japanese_title_generation.ipynb)
    - Bandoluが[PyTorch Lightning](https://www.pytorchlightning.ai/)のバージョン違いによる記述の書き換えを行いました
- [ニュース記事本文生成（文章生成）](https://colab.research.google.com/github/sonoisa/t5-japanese/blob/main/t5_japanese_article_generation.ipynb)



## 転移学習済みモデルを用いた推論の例

- [ニュース記事のタイトル生成（一種の文章要約）の推論のみ](https://colab.research.google.com/github/sonoisa/t5-japanese/blob/main/t5_japanese_title_generation_inference.ipynb)
- [ニュース記事本文生成（文章生成）の推論のみ](https://colab.research.google.com/github/sonoisa/t5-japanese/blob/main/t5_japanese_article_generation_inference.ipynb)
