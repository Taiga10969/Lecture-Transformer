# Lecture-Transformer
MPRG新B4向け春の勉強会用資料<br>
<br>
テーマ：lecture 中級編3(再帰ネットワーク)<br>
内　容：RNN，Attention seq2seq，**Transformer**<br>
<br>
今は大Transformer時代！<br>
研究でもTransformer系のモデルを使う人が多いことから主にTransformerについて解説します．<br>
<br>

**Transformerのモデル構造**<br>
<img src="https://github.com/Taiga10969/Lecture-Transformer/assets/106218669/cc0a487c-f35c-4f37-86f7-0ee313ad1f9b" width="400">


## 写経しながら理解するTransformer (copy-code_Transformer)
自分は，Transformerをコードを写経して理解した人です！<br>
Pythonの理解もまだまだ...研究ではプログラムを改変したりしないと行けいない...<br>
だからこそ！プログラムを写経しながらPythonも理解しつつ，Transformerもコードレベルで理解してみてはいかが？
- **copy_code_Transformer_01_Embedder.ipynb**<br>
  Transformerに入力したトークンID列を埋め込みベクトルに変換する機構
- **copy_code_Transformer_02_PositionalEncoder.ipynb**<br>
  各トークンをあらわす埋め込みベクトルに対して位置情報 PE を付与する機構
- **copy_code_Transformer_03_Multi_Head_Attention.ipynb**<br>
  Transformerに組み込まれている他のトークンとの関連度を考慮した特徴抽出を行うMulti-Head Attention機構
- **copy_code_Transformer_04_FeedFowardNetwork.ipynb**<br>
  各トークンのベクトルごとに非線形変換処理を行う機構
- **copy_code_Transformer_05_Transformer.ipynb**<br>
  最終的に01〜04で作成した各機構のクラスを用いてTransformerを構築
