# Unbalanced_Data
* 不均衡データの処置プログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── Dockerfile                Dockerファイル
├── notebook                  jupyter notebook
└── data                      dataファイル
```

## 環境構築
Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Unbalanced_Data）
```
cd Desktop/Unbalanced_Data
```
Dockerによる環境構築
```
docker build .
```
docker run実行（対象フォルダをマウントする／例：Desktop/Unbalanced_Data）
```
docker run -p 8888:8888 -v ~/Desktop/Unbalanced_Data/:/work --name Unbalanced_Data <docker image>
```
ブラウザーを立ち上げてlocalhost:8888へアクセス
workフォルダ内が対象フォルダにマウントされている

## jupyter notebook説明
* Unbalanced_Data.ipynb : 不均衡データの処置のnotebook
* imbalanced_data.ipynb : チュートリアルのnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3