# Unbalanced-Data
* 不均衡データの処置プログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
├── notebook                  jupyter notebook
└── data                      dataファイル
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Unbalanced-Data）
```
cd Desktop/Unbalanced-Data
```

* Dockerによる環境構築（フォルダをマウント：Desktop/Unbalanced_Data）
```
docker-compose up
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* Unbalanced_Data.ipynb : 不均衡データの処置のnotebook
* imbalanced_data.ipynb : チュートリアルのnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
