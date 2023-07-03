# 図メモ

- [GCPアーキ図サンプル](https://drawio-app.com/blog/updated-google-cloud-platform-icons-and-templates/#)
- [公式](https://cloud.google.com/icons?hl=ja)

# フロント関連

- [ISR](https://zenn.dev/akino/articles/78479998efef55)
- [gzip圧縮のトランスコーディング](https://cloud.google.com/storage/docs/transcoding?hl=ja)
  - ネットワーク帯域の節約と高速化のため
  - 画像などに関してはGCSへgzip形式で配置し、[CloudRunからのOutBound方向のデータ転送量を節約する](https://masutaka.net/2022-11-04-1/#%E5%86%85%E8%A8%B3)

# アーキ関連

## FireStore

- https://zenn.dev/google_cloud_jp/articles/a0a6b5f855fe90
- https://cloud.google.com/architecture/building-scalable-apps-with-cloud-firestore?hl=ja
- [FireStoreのインデックス](https://firebase.google.com/docs/firestore/query-data/index-overview?hl=ja)

## ComputeEngine

- [PersistentDisk](https://cloud.google.com/compute/docs/disks/add-persistent-disk?hl=ja)

# CI/CD関連

- [CloudRunへのデプロイアクション](https://github.com/google-github-actions/deploy-cloudrun)