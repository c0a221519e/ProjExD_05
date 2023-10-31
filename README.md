# ファイタージェット

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
- シューティングゲーム
- 背景のみ動く
- スコアは時間経過と敵を倒したら加算
- 敵は白・緑・赤・紫(仮)
- 一定時間が経過したらボス登場．ボスはランダムで白と緑の雑魚キャラを一定時間が経過するごとに召喚

## ゲームの実装
###共通基本機能
* キャラを管理する関数
* スコアに関する関数
* 敵のHP管理関数

### 担当追加機能
* 森田 [キャラの実装]
* しなだ [HP]
* ろくまいる [背景]
* りっきー [タイマーとスコア関数]
### ToDo
- [ ] main関数
- [ ] 背景とキャラの実装
- [ ] スコア関数
- [ ] HP&当たり判定
### メモ
* 一旦それぞれが頭の中に描いてることをそのまま書く．後から擦り合わせていく．