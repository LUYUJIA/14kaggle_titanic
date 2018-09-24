# kaggle
- データから予測を行い精度を競い合う
  - expert:ブロンズ２個(上位１０％)
  - master:ゴールド１回（トップ１０）、シルバー2回（上位5%）
- [kaggleとは](http://www.currypurin.com/entry/2018/02/21/011316)
- [DeNAのkaggle制度](https://dena.ai/kaggle/)
- [kaggleをやる意義](https://www.slideshare.net/HaradaKei/devsumi-2018summer)
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
- [Titanic](https://www.kaggle.com/c/titanic/leaderboard)
- pandas,sklearnによる前処理はカンペ形式にする（覚えるの(ヾﾉ･∀･`)ﾑﾘﾑﾘ）
- keras使ったほうがいい感が凄い
- TensorFlowのドキュメントがよくわからない
- データ数の問題で、学習と評価への分け方次第で学習が決まってしまっている

## 参考
- [TensorFlow回答例](https://www.kaggle.com/linxinzhe/tensorflow-deep-learning-to-solve-titanic)
- [keras日本語ドキュメント](https://keras.io/ja/)
- [sklearn_preprocess](http://own-search-and-study.xyz/2016/11/23/sklearn%E3%81%AEpreprocessing%E3%81%AE%E5%85%A8%E3%83%A1%E3%82%BD%E3%83%83%E3%83%89%E3%82%92%E8%A7%A3%E8%AA%AC/)
- [pandas](https://qiita.com/tanemaki/items/2ed05e258ef4c9e6caac#各種統計量)
- [kaggle回答例](http://www.mirandora.com/?p=1804)

## 特徴量エンジニアリング　
- [特徴量エンジニアリングまとめ](http://kamonohashiperry.com/archives/1054) 
- [テクニックまとめ](https://github.com/nejumi/kaggle_memo)

## kaggleコンテンツ
- [kaggleブログ](http://www.currypurin.com/)
- [kaggle Slack](https://kaggler-ja.slack.com/messages/C0M91A5FX/)
- [Coseraのkaggle講座](https://www.coursera.org/learn/competitive-data-science)
- kaggler　Youtube

## コラム
- [Proto kagglerの解法](https://employment.en-japan.com/engineerhub/entry/2018/08/24/110000)
- [onodera san](https://japan.zdnet.com/article/35124706/2/)
- [catboost,ベイズ最適化](http://www.mirandora.com/?p=2505#menu2)
- [何故Gini係数を重要度に用いるのか](http://socinuit.hatenablog.com/entry/2018/08/23/201357)
- [ROC,AUC](http://www.randpy.tokyo/entry/roc_auc)
## コラム、
## コラム
