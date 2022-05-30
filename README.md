# M1MBA_ResolutionExtend

M1 MacBookAirの擬似解像度に1920x1200を追加するやつ

## (自分の)環境

- M1 MacBookAir(Late2020) 16GB/1TB
- macOS Monterey 12.4

## 前提条件

Macの[システム環境設定]->[ディスプレイ]->[カラープロファイル]->[カスタマイズ]->[カラーLCD]を選択  
  
スクロールボックスの[mmod]選択時に[製造元:00000610][機種:0000A045]の場合、使用可能  
  
![image](https://user-images.githubusercontent.com/78929673/171062061-5d24f348-1c8e-439e-ae80-5148f37cecca.png)

## つかいかた

1. なんか適当な所でgit cloneする(Download Zipでもええけど)
```
git clone [このレポ]
```

2. /Library 配下にcloneした[Displays]フォルダをコピペ
3. mac再起動
4. [システム環境設定]->[ディスプレイ]で解像度を選択する所になんか増えてるはずです  
  
![image](https://user-images.githubusercontent.com/78929673/171062510-54a5dd55-2c39-4e38-9887-331b8f66b94d.png)

5. 以上

参考...https://dev.classmethod.jp/articles/m1-macbook-air-13inch-1920x1200/
