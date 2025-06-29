# web-tiny-rogue-like

ローグライクっぽい感じのやつです。クラシックなASCII表示で、ランダム生成されるダンジョンを探索しましょう。

伝統的なローグライクゲームをWebブラウザで手軽に楽しめるように実装しました。

ランダムに生成されるダンジョンを探索し、敵を倒しながら深層を目指します。

![image](https://github.com/user-attachments/assets/b051918c-98d7-4bb2-8de3-65450cdfa7f1)

https://you-sk.github.io/web-tiny-rogue-like/

## ✨ 特徴

- **ランダムダンジョン生成**: 毎回異なるマップレイアウト
- **ターン制バトル**: 伝統的なローグライクスタイルの戦闘
- **階層システム**: 深く潜るほど難易度が上昇
- **回復アイテム**: ポーションで体力を全回復
- **レトロな見た目**: グリーンディスプレイ風のASCII表示
- **即座に再挑戦**: ゲームオーバー後もすぐにリトライ可能

## 🕹️ 操作方法

| キー | アクション |
|------|------------|
| 矢印キー / WASD | 移動 |
| スペース | 足踏み（その場で待機） |
| > | 階段を降りる（階段の上で） |
| R | ゲームオーバー時に再開 |

### 💡 ヒント
- 壁に向かって移動すると足踏みになります（敵だけが行動）
- HPが少ない時は通路で敵を待ち伏せしましょう
- ポーションは戦略的に使いましょう

## 🎯 ゲーム要素

### キャラクター
- **@** (シアン): プレイヤー
- **g** (赤): ゴブリン（敵）
- **!** (マゼンタ): ポーション
- **>** (黄): 階段
- **#**: 壁
- **.**: 床

### ゲームシステム
- **HP**: 20（初期値）
- **ダメージ**: プレイヤー2、敵1
- **階層ボーナス**: 階段を降りるとHP+5回復
- **敵の増加**: 5階ごとに敵が1体追加
- **ポーション**: 1-4階は1個、5階以降は2個配置

## 🛠️ 技術仕様

- 純粋なHTML/CSS/JavaScript（外部ライブラリ不使用）
- レスポンシブデザイン
- モダンブラウザ対応

## 📄 ライセンス

MIT License で公開しています。
