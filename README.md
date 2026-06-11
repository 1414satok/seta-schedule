# SETA 2026 Schedule

iPhone向けインタラクティブスケジュールツール for [SETA 2026](https://sites.google.com/view/seta2026/) (Symposium on Econometric Theory and Applications)

**会期:** 2026年6月13日（土）〜 14日（日）  
**会場:** 東京大学 本郷キャンパス（講義室 1, 2, 3, 6, 7）

## 公開URL

**https://1414satok.github.io/seta-schedule/**

## 機能

- **グリッド表示** — 縦軸が時間、横軸が会場（Room 1/2/3/6/7）
- **セッション詳細** — セッションをタップするとボトムシートで発表一覧を表示
- **発表ごとのチェック** — 聴きたい発表を1件ずつチェック（全選択・全解除も可）
- **マイ予定** — チェックした発表を日別・時間順でまとめて確認
- **オフライン保持** — 選択状態はブラウザの localStorage に保存

## iPhoneでの使い方

1. Safari で上記URLを開く
2. 共有ボタン（□↑）→「ホーム画面に追加」でアプリ風に起動可能

## 技術スタック

- 単一の `index.html`（外部依存なし）
- CSS Grid + `position: sticky` による縦横スクロール対応グリッド
- Web Storage API (localStorage) でチェック状態を永続化
- iPhone Safe Area / Dynamic Island 対応
