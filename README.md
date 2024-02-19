# Lecture-Transformer
**MPRG新B4向け春の勉強会用資料**<br>
<br>
テーマ：lecture 中級編3(再帰ネットワーク)<br>
内　容：RNN，Attention seq2seq，**Transformer**<br>

日程調整：[勉強会_日程調整]([http://tonton.amaneku.com/list.php?id=20240217050454_gZDs5s](https://tonton.amaneku.com/list.php?id=20240219061002_qEO9D4))　← 早めに回答の程よろしくお願いします
<br>
今は大Transformer時代！<br>
研究でもTransformer系のモデルを使う人が多いことから主にTransformerについて解説します．<br>
<br>

**Transformerのモデル構造**<br>
<img src="https://github.com/Taiga10969/Lecture-Transformer/assets/106218669/cc0a487c-f35c-4f37-86f7-0ee313ad1f9b" width="400">
***
### 写経しながら理解するTransformer (copy-code_Transformer)
自分は，Transformerをコードを写経して理解した人です！<br>
Pythonの理解もまだまだ...研究ではプログラムを改変したりしないと行けいない...<br>
だからこそ！プログラムを写経しながらPythonも理解しつつ，Transformerもコードレベルで理解してみてはいかが？
- [copy_code_Transformer_01_Embedder.ipynb](https://github.com/Taiga10969/Lecture-Transformer/blob/main/copy_code_Transformer_01_Embedder.ipynb)<br>
  →Transformerに入力したトークンID列を埋め込みベクトルに変換する機構
- [copy_code_Transformer_02_PositionalEncoder.ipynb](https://github.com/Taiga10969/Lecture-Transformer/blob/main/copy_code_Transformer_02_PositionalEncoder.ipynb)<br>
  →各トークンをあらわす埋め込みベクトルに対して位置情報 PE を付与する機構
- [copy_code_Transformer_03_Multi_Head_Attention.ipynb](https://github.com/Taiga10969/Lecture-Transformer/blob/main/copy_code_Transformer_03_Multi_Head_Attention.ipynb)<br>
  →Transformerに組み込まれている他のトークンとの関連度を考慮した特徴抽出を行うMulti-Head Attention機構
- [copy_code_Transformer_04_FeedFowardNetwork.ipynb](https://github.com/Taiga10969/Lecture-Transformer/blob/main/copy_code_Transformer_04_FeedFowardNetwork.ipynb)<br>
  →各トークンのベクトルごとに非線形変換処理を行う機構
- [copy_code_Transformer_05_Transformer.ipynb](https://github.com/Taiga10969/Lecture-Transformer/blob/main/copy_code_Transformer_05_Transformer.ipynb)<br>
  →最終的に01〜04で作成した各機構のクラスを用いてTransformerを構築


***
### 今回の勉強会のテーマに関連する[MPRGDeepLearningLectureNotebook](https://github.com/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/tree/master)<br>
**中級3：PyTorchで作る再帰型ネットワーク**
1.  [Recurrent Neural Networkによる電力予測](13_rnn/01_03_RNN.ipynb) [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/blob/master/13_rnn/01_03_RNN.ipynb)
2.  [Encoder-Decoderによる計算機作成](13_rnn/04_Seq2Seq.ipynb) [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/blob/master/13_rnn/04_Seq2Seq.ipynb)
3.  [Attention Seq2seqによる計算機作成](13_rnn/05_Attention.ipynb) [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/blob/master/13_rnn/05_Attention.ipynb)
4.  [Attention Seq2seqによる日付変換](13_rnn/05_Attention_alpha.ipynb) [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/blob/master/13_rnn/05_Attention_alpha.ipynb)
5.  [Transformerによる計算機作成](13_rnn/06_Transformer.ipynb) [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/blob/master/13_rnn/06_Transformer.ipynb)
4.  [Convolutional LSTMを用いた動画像予測](13_rnn/07_ConvLSTM.ipynb) [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/machine-perception-robotics-group/MPRGDeepLearningLectureNotebook/blob/master/13_rnn/07_ConvLSTM.ipynb)
