# kaggle_titanic
- https://www.kaggle.com/c/titanic/leaderboard
## 目的
- kaggleのやり方を覚える
- 処理のフレームワークを作る
- TensorFlowで、DeepLearningする
- 決定木系統を復習する[決定木勉強まとめ](https://github.com/dialectic4th/06desition_tree_system)

## [kaggleAPI導入](http://www.currypurin.com/entry/2018/kaggle-api)
- pip3インストール
- tokenを入手
  
```
#ダウンロード
kaggle competitions download -c titanic

#コミット
kaggle competitions submit -c titanic -f submission.csv -m "test"
```



## 感想
- pandas,sklearnによる前処理はカンペ形式にする（覚えるの(ヾﾉ･∀･`)ﾑﾘﾑﾘ）
- keras使ったほうがいい感が凄い
- TensorFlowのドキュメントがよくわからない
- データ数の問題で、学習と評価への分け方次第で学習が決まってしまっている

## 参考
- [TensorFlow回答例](https://www.kaggle.com/linxinzhe/tensorflow-deep-learning-to-solve-titanic)
- [keras日本語ドキュメント](https://keras.io/ja/)
- [sklearn_preprocess](http://own-search-and-study.xyz/2016/11/23/sklearn%E3%81%AEpreprocessing%E3%81%AE%E5%85%A8%E3%83%A1%E3%82%BD%E3%83%83%E3%83%89%E3%82%92%E8%A7%A3%E8%AA%AC/)
- [pandas](https://qiita.com/tanemaki/items/2ed05e258ef4c9e6caac#各種統計量)
