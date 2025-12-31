# 脳外科講座プロジェクト

## 環境設定
[mamba](https://github.com/conda-forge/miniforge)のインストール
```
# mambaのダウンロード
cd ~/Download
curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"

# mambaのインストール
bash Miniforge3-$(uname)-$(uname -m).sh

# 環境の作成
mamba create -n neuro python=3.10

# 環境の起動
mamba activate neuro
```

## パッケージのインストール
```
mamba install pandas matplotlib jupyter nbclassic
mamba install conda-forge::neurokit2
```
