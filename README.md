# Real-Estate-Price-Forecasting
  Nishika　中古マンション価格予測 2022夏の部  
  https://www.nishika.com/competitions/34/summary
  
概要  
・目的変数は、取引価格（総額）について常用対数をとった「取引価格（総額）_log」  
・予測精度の評価は、MAE  

最終提出ファイル  
・LightGBMにて、目的変数を①『取引価格（総額）_log』、②『坪単価』の２つのモデルを作成  
・optunaにて部分的なベストパラメータの探索を複数回行った上、それらでの予測の平均値から最終予測値を算出  

最終スコア：0.074365  
最終順位：参加497人中、10位  
