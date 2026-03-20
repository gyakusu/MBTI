# 更新履歴 (Changelog)

`openclaw-16mbti` Skill に関するすべての重要な変更はここに記録されます。本ログは [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/) 規範に従い、[セマンティックバージョニング](https://semver.org/lang/zh-CN/)を採用しています。

## [Unreleased]

- 実機テストとプロンプト微調整のフィードバック待ち。

---

## [1.0.0] - 2026-03-09

### Added (追加)

- **コアロジック接続 (SKILL.md)**：中枢呼び出しファイルの設計を完了し、`task_mode` と `output_style` の正確な識別をサポート。
- **3種類の出力モードルーティング**：
  - 【単一流派設定】 `single`
  - 【極性推論対立】 `compare`
  - 【システム知能配牌】 `recommend`
- **レッドラインと免責ブロック機構**：設定ファイルの下層に「反医療診断」、「反採用選考」の高優先度ブロックロジックを強制的に組み込み。
- **全系キャラクターコンポーネントパッケージ (profiles/)**：
  - NT アーキテクチャグループ (INTJ, INTP, ENTJ, ENTP)
  - NF 価値グループ (INFJ, INFP, ENFJ, ENFP)
  - SJ 安定グループ (ISTJ, ISFJ, ESTJ, ESFJ)
  - SP 臨機グループ (ISTP, ISFP, ESTP, ESFP)
- **機械可読インデックス設定**：外部プロセス呼び出し用に `03_personality_profiles.json` と `.yaml` を生成。
- **付属ヘルプドキュメント**：`README.md`、使用例説明 `examples.md`、出荷テスト検証基準 `tests.md` を作成。

### Changed (変更)

- *なし (初回リリース)*

### Fixed (修正)

- *なし (初回リリース)*
