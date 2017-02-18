
## これは何？
sharelatexで日本語が使えるようにいろいろいじったモノ

## Install
すべてrootでやる

```
pip install docker-compose # ←ここでv1.11.1以上がインストールされていることを確認！
cd ~/
git clone https://github.com/sidepelican/sharelatex
git clone https://github.com/sidepelican/sharelatex-docker-image
cd sharelatex
docker-compose build # --no-cacheでキャッシュ無効化
docker-compose up -d
```
