# 更新履歴（Changelog）

`openclaw-16mbti` スキルに関するすべての重要な変更はここに記録されます。本ログは [Keep a Changelog](https://keepachangelog.com/ja/1.0.0/) の規約に従い、[セマンティックバージョニング](https://semver.org/lang/ja/)を採用しています。

## [Unreleased]

- 実機テストおよびプロンプト微調整フィードバックを待機中。

---

## [1.0.0] - 2026-03-09

### Added（新規追加）
- **コアロジック接続（SKILL.md）**：`task_mode` および `output_style` の正確な識別をサポートする中枢呼び出しファイルの設計を完了。
- **3種類の出力モードルーティング**：
  - 【シングルペルソナ設定】 `single`
  - 【極性推演対立】 `compare`
  - 【システム自動発牌】 `recommend`
- **レッドライン・免責ブロック機構**：設定ファイルの底層に「反医療診断」「反採用選別」の高優先ブロックロジックを強制的に書き込み。
- **全系ロールコンポーネントパック（profiles/）**：
  - NT アーキテクチャ群（INTJ, INTP, ENTJ, ENTP）
  - NF 価値観群（INFJ, INFP, ENFJ, ENFP）
  - SJ 安定群（ISTJ, ISFJ, ESTJ, ESFJ）
  - SP 臨場群（ISTP, ISFP, ESTP, ESFP）
- **機械可読インデックス設定**：外部プロセス呼び出し用の `03_personality_profiles.json` と `.yaml` を生成。
- **付帯ヘルプドキュメント**：`README.md`、使用ケース説明 `examples.md`、出荷テスト検証基準 `tests.md` を作成。

### Changed（変更）
- *なし（初回リリース）*

### Fixed（修正）
- *なし（初回リリース）*
