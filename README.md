
# Transformerのencoder部分から出力されるベクトルを使用して文を評価できないのだろうか？(自動評価タスクに使用できないか？)


  今まで気になっていたことを色々試してみたのですが、どこにも見せる場がないので、ここに記そうと思います。
#

## 詳しくはQiitaに書きました


## 以下はコードの説明です。

## melt_japan.py

17 model_path = ".../fasttext_PATH"#fasttextのモデルへのパス  
の部分にfasttextのモデルへのパスを設定してください

22 with open('.../ref_PATH', 'r') as f:#参照訳へのパス  
の部分に参照訳へのパスを設定してください

39 with open('.../MT_PATH', 'r') as f:#MT訳へのパス  
の部分にMT訳へのパスを設定してください







