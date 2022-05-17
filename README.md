# Sentiment_Analysis_en
Twitterのツイート（英語表記のみ）を用いて、ネガティブ・ポジティブを予測する感情分析モデルを構築しました。

## Overview
感情分析の流れ
- セットアップ
- データの前処理
- ベースモデル構築、学習、評価
- 学習プロセス可視化（ベースモデル）
- 過学習対策モデルの構築、学習、評価
- 学習プロセス可視化（過学習対策モデル）
- モデルの評価
- サンプリング
- エラーにおける頻出単語Top20
    - 前処理 
    - 可視化
- 感情スコア算出
- 検証
    - 記号の有無
    - URLの有無
    - 'mの有無
    - quotの有無
    - 数字の有無
    - 文脈を考慮した予測かどうか
- モデルの保存と読み込み

## Description
感情分析の詳細については以下のブログを確認する事
- [技術ブログ](https://leadinge.co.jp/rd/2022/04/27/1888/)

## Requirements
- Google Colaboratory
- Python==3.7.13
- tensorflow==2.8
- keras==2.8.0
- sklearn==1.0.2
- numpy==1.21.6
- pandas==1.3.5
- matplotlib==3.2.2
- seaborn==0.11.2
- nltk==3.2.5
