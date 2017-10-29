# Melody Maker

[![Product Name](https://www.youtube.com/watch?v=Du_0OMl3P_8&feature=youtu.be)

## 製品概要
### :notes: sound design Tech :notes:

### 背景とターゲット
#### 背景

 普段目に見えないデータを音に変換することで、これまでに聞いたことのない音色の変化や楽曲を自動生成したかった。

　” That’s what I love about music.  
 One of the most banal scenes is suddenly invested… with so much meaning.”  はじまりのうた　


#### 着目した顧客・顧客の課題・現状　

*  着目した顧客：

   * 音楽を演奏する人 → インタラクティブな新しい楽器としての利用
   * 音楽を聴く人 → 環境に合わせたBGM
   * 音楽の利用者 → ロイヤリティフリーなBGM素材として利用

*  現状と課題：

  情報の可聴化の研究は存在するが、音楽として楽しめる形でアウトプットするものがない。

  参考文献：
 http://sonification.de/publications/media/Hermann2008-TAD.pdf

 情報を楽しめる形で可聴化、演奏家が使えるような実用的プロダクトの作成を目指す。
　
### 製品説明
### 特長
* 特長１

  音と関係ないデータを可聴化し音楽を自動で生成します。コード進行のデータベースとマルコフ連鎖によってコードを遷移させます。[](コードトーンを引数に取り、メロディやベースの音を追加することによって音楽が自動生成される。)

* 特長2

  楽器として利用可能です。センサ情報を楽器のコントロールに使用することで意図的な操作を超えたサウンドを生み出します。

* 特長3

  心地よいサウンドメイキングを目指しています。AIを用いて環境にコグニティブなサウンドメイキングを可能にするのが目標です。

### 解決出来ること
使用量が発生しないBGM

### 今後の展望
楽器として楽しめるUI  
他の楽器との同期  
拡張性の向上（ネット上のデータを利用）  
MIDIをデータ出力して外部音源と連携  
生成アルゴリズムの改善 
AIを用いた心地よいサウンドメイキング

## 開発内容・開発技術
### 活用した技術

#### API・データ
* センシングデータ

#### フレームワーク・ライブラリ・モジュール
* The Synthesis tookkit
* WiringPi

#### デバイス
* raspberry pi2
* ジャイロ、温度、カメラセンサー

#### 設計ツール
* Fusion 360

### 研究内容・事前開発プロダクト
* 特になし

### 独自開発技術
#### 2日間に開発した独自の機能・技術
* 美しいデザインの筐体（アクリル板加工＆３Dプリント）
* マルコフ連鎖に基づいた拡張性のあるサウンド生成アルゴリズム
