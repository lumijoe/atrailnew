# atrailnew

## 11/21 より html 起こし

## ダミー画像を使用したい時

img src="https://via.placeholder.com/253x45"

## Bootstrap でカスタムする

## Git 通信パケットが大きすぎて push が失敗する時

3. 送信パケットサイズの問題を確認
   送信パケットが大きすぎて git push が失敗している場合、以下を試す

git config --global http.postBuffer 524288000
git push origin main

## コードMerge自宅会社
1125