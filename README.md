# 概要

- プレイヤーのゲーム勝利数を保存できる Web サーバー
  - プレイヤーの勝利数を返す
    - GET /players/{name}
  - 勝利したプレイヤー名を記録し、勝利数を増分した値を返す
    - POST /players/{name}

# 目的

- Go でテスト駆動開発を経験する
