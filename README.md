# マーダーミステリーデータセット

## Overview
このリポジトリは、マーダーミステリーゲームのデータセットを公開しています。
他のドメインで学習した嘘つき検出モデルの検証用データセットとして作成しました。

## Dataset Description
- `ts`: タイムスタンプ
- `speakers`: 話者のキャラクター名
- `messages`: 発話
- `lie`: 嘘の発話(犯人のみアノテーション可能)
- `suspicious_〇〇`: プレイヤー〇〇が怪しいと思った発話
- `reason_〇〇`: プレイヤー〇〇が発話を怪しいと思った理由
- `deciding_factor_〇〇`: プレイヤー〇〇が投票先を決める際の決定要因
- `vote_target_〇〇`: プレイヤー〇〇の投票対象
- `vote_reason_〇〇`: プレイヤー〇〇の投票理由
- `channel_name`: チャンネル名
- `criminal`: 犯人のキャラクター名
- `has_criminal_won`: 犯人が勝利したかどうか
- `points`: 各キャラクターの獲得ポイント
- `scenario_title`: シナリオのタイトル
- `scenario_url`: シナリオのURL

## Scenario
本データセットは、以下のシナリオを利用しています。

※本研究で使用するログデータはシナリオ制作者から研究目的で利用する許可を得ており、ネタバレを防ぐための対策としてZipファイルにて公開しています。

| タイトル | プレイヤー数 | 実施回数 | URL |
|----------|--------------|----------|------------------------------|
| 見やるは、誰ぞ、 | 3 | 2 | https://booth.pm/ja/items/3690322 |
| ワタナベ | 3 | 2 | https://www.joymada.com/madanabi/6259/ |
| つづりあわせの流儀 | 3 | 1 | https://kitankan.com/scenario/ryugi/index.html |
| 死者の湯加減 | 4 | 2 | https://booth.pm/ja/items/2231685 |


## Cite
```
@INPROCEEDINGS{aoki2024,
  title     = "日本語表現での嘘つき検出器構築と汎用性検証",
  booktitle = "2024年度 人工知能学会全国大会 (第38回)",
  author    = "青木洋繁 and 狩野芳伸",
  publisher = "人工知能学会",
  month     =  may,
  year      =  2024,
}
```
