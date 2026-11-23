# decisions: 決定履歴（新しいものを下に追記）

形式: `- YYYY-MM-DD: 決定内容（理由）`  ※機密は書かない。

- 2026-11-19: CLAUDE.md・AGENTS.md・decisions.md・notes/ を作成（その時点の index.html を読んで現状を要約）。
- 2026-11-19: 壁打ちの中身（背景・こだわり・却下案）は notes/ に日付つきで残す。
- 2026-11-19: クラウド版 Claude Code の変更も main に直接 push する（作業用ブランチのままだと次のセッションが読めないため。Satoshi承認、全リポジトリ共通）。
- 2026-11-23: ゲーム要素を追加（キャラカード収集16種＋パック、ごほうびリスト）。データは localStorage の同じキーに cards / rewards を後付けし、古いデータは norm() で補う。書き出しJSONは version:1 のまま cards / rewards を任意項目で追加。詳細は notes/2026-11-23-ゲーム要素の追加.md
