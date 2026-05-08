# PROJECT_JOURNAL

## TAKORON たいこゲーム v1 仕様メモ

### 目的
3歳児向けに、難しいリズムゲームではなく、ボタンを押すとすぐ反応する「押すだけ反応ゲーム」として作る。

### 基本方針
- 画面に「ポン！」が出たらボタンを押す
- 押せばだいたい成功
- タイミングがズレても怒らない
- 連打しても楽しい
- TAKORONが太鼓を叩く
- MIKAROは手なしの姿で横から応援する

### 画面
1. スタート画面
2. ゲーム画面

### 基準サイズ
- スマホ縦画面
- 390 x 844 想定

### アセット構成
- 背景、タイトル、キャラクター、太鼓、ボタン、効果音アイコンを分離する
- タイトル画像は揺らせるように独立画像にする
- TAKORONは複数画像でアニメーションさせる

### TAKORON画像
- takoron_idle.png
- takoron_hit_left.png
- takoron_hit_right.png
- takoron_hit_center.png
- takoron_success_1.png
- takoron_success_2.png

### MIKARO画像
- mikaro_cheer.png
- MIKAROに手・腕・指は付けない

### UI画像
- button_start.png
- button_pon.png
- score_panel.png
- star_panel.png
- instruction_banner.png

### 効果画像
- effect_pon.png
- effect_don.png
- effect_pan.png
- effect_kira.png
- effect_hit_flash.png
- effect_music_notes.png

### 操作
- スマホ：ポンボタンをタップ
- PC：Spaceキーでも反応

### 今回やらないこと
- 難しいリズム判定
- ミス判定
- ゲームオーバー
- キャラ選択
- ステージ選択
- ランキング
- セーブ機能
