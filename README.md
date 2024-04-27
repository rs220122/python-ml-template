# Python MLプロジェクト　テンプレート

## ファイル構成
```
installation: 環境セットアップに使うファイルを格納。 (`Dockerfile`, `requirements.txt`, `conda_env.yaml` etc)
docs: ドキュメントを格納(アーキテクチャ図、フローチャート、シーケンス図など)
pipelines: 機械学習パイプライの格納
src: ソースコードの格納
```

## 環境セットアップ
例
```
pip install -r installation/requirements.txt
conda env create -f conda_env.yaml
```


## 実行方法
```
python main.py
```