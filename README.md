# M1MBA_ResolutionExtend

M1 MacBookAirの擬似解像度に1920x1200を追加するやつ

## (自分の)環境

- M1 MacBookAir(Late2020) 16GB/1TB
- macOS Monterey 12.4 -> Ventura 13.0 -> Ventura 13.3

## 前提条件

### 13.2以前

Macの[システム環境設定]->[ディスプレイ]->[カラープロファイル]->[カスタマイズ]->[カラーLCD]を選択  
  
スクロールボックスの[mmod]選択時に[製造元:00000610][機種:0000A045]の場合、使用可能  
  
![image](https://user-images.githubusercontent.com/78929673/171062061-5d24f348-1c8e-439e-ae80-5148f37cecca.png)

### 13.3以降

> アップデート後、ディスプレイの機種IDが[0000A045]から[0000A047]に数値が変わっていた為、要確認

Macの[システム環境設定]->[ディスプレイ]->[カラープロファイル]->[カスタマイズ]->[カラーLCD]を選択  
  
スクロールボックスの[mmod]選択時に[製造元:00000610][機種:0000A047]の場合、使用可能  

![image](https://user-images.githubusercontent.com/78929673/230288819-4c5019e0-360f-4582-b23f-2df0b9730501.png)

## つかいかた

1. なんか適当な所でgit cloneする(Download Zipでもええけど)

```
git clone [このレポ]
```

2. ~/Library 配下にcloneした[Displays]フォルダをコピペ~

### 13.2以前
/Library 配下にcloneした[under_13.3]フォルダ内の[Displays]フォルダをコピペ

### 13.3以降  
/Library 配下にcloneした[over_13.3]フォルダ内の[Displays]フォルダをコピペ

3. mac再起動
4. [システム環境設定]->[ディスプレイ]で解像度を選択する所になんか増えてるはずです  
  
- macOS Monterey
![image](https://user-images.githubusercontent.com/78929673/171062510-54a5dd55-2c39-4e38-9887-331b8f66b94d.png)

- macOS Ventura
![image](https://user-images.githubusercontent.com/78929673/198668466-dcb3e377-d019-4b65-b057-8ff7a06f50e8.png)

5. 以上

参考...https://dev.classmethod.jp/articles/m1-macbook-air-13inch-1920x1200/
