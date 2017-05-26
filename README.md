# CNTK Hands-On
「CNTK を使った CNN による画像認識」のハンズオン用レポジトリです。

# Hands-On 資料

## 0. 環境構築

ローカルで環境構築される場合：

[Installing CNTK for Python on Windows](https://github.com/Microsoft/CNTK/wiki/Setup-Windows-Python#anaconda3

[Installing CNTK for Python on Linux] (https://github.com/Microsoft/CNTK/wiki/Setup-Linux-Python)

 

Azure の場合：

[Deep Learning toolkit for Data Science VM](https://azuremarketplace.microsoft.com/ja-jp/marketplace/apps/microsoft-ads.dsvm-deep-learning?tab=Overview)

Azure 上では、Windows 版の最初から GPU Version で環境構築された VM イメージが MarketPlaceから出ています。



## 1. 本ハンズオンの概要および前提知識のおさらい

以下に、本ハンズオンの概要およびハンズオンを実施するうえで最低限必要となる事前知識についてまとめています。

[ハンズオン説明資料](https://github.com/msmamita/cntk_handson/blob/master/CNTK_Beginner's_HandsOn_DecodeHackday.pptx)

## 2. 事前準備 (使用するデータの前処理)

ハンズオンを開始する前に、以下のように、DataLoader_CIFAR10.py を実行し、ハンズオンで使用する CIFAR-10 データをダウンロードしてください。

```py
python DataLoader_CIFAR10.py 
```

## 3. ハンズオン開始

それでは、ハンズオンを開始しましょう。 
本ハンズオンは、[こちらの Jupyter notebook 形式](https://github.com/msmamita/cntk_handson/blob/master/CNTK_Handson_ImageRecongnition_w_CNN.ipynb)の資料を用いて実施していただきます。


# 参考情報
* [Python API for CNTK](https://www.cntk.ai/pythondocs/index.html)
* [CNTK公式ページ](https://github.com/Microsoft/CNTK)
