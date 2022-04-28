# try-codeclimate-cli

VSCode の Remote Containers で Code Climate CLI 動くか実験

* イマイチ
  * devcontainer.json の `feature`:`docker-from-docker` を使うとイメージビルド後に動く問題
    * Rebuild の時間が長くなる
    * codeclimate 本体の make install を Dockerfile でできない

→ `unuse-feature` branch に上の問題解決したものあり〼
