# 更新履歴 (Changelog)

`openclaw-16mbti` Skill に関するすべての重要な変更はここに記録されます。本履歴は [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/) の規約に従い、[セマンティックバージョニング](https://semver.org/lang/zh-CN/) を採用しています。

## [Unreleased]

- 実機テストおよびプロンプト微調整のフィードバック待ち。

---

## [1.0.0] - 2026-03-09

### Added (追加)
- **コアロジックの接続 (SKILL.md)**：`task_mode` および `output_style` の正確な認識をサポートする、中枢呼び出しファイルの設計を完了。
- **3種類の出力モードルーティング**：
  - 【単一流派設定】 `single`
  - 【極性推論対立】 `compare`
  - 【システムスマート配牌】 `recommend`
- **レッドラインおよび免責ブロック機能**：設定ファイルの基盤レベルで「医療診断への反用」「採用選考への反用」を強制的に禁止する高優先ブロックロジックを実装。
- **全系統キャラクターコンポーネントパッケージ (profiles/)**：
  - NT 構造グループ (INTJ, INTP, ENTJ, ENTP)
  - NF 価値グループ (INFJ, INFP, ENFJ, ENFP)
  - SJ 安定グループ (ISTJ, ISFJ, ESTJ, ESFJ)
  - SP 即興グループ (ISTP, ISFP, ESTP, ESFP)
- **機械可読インデックス設定**：外部プロセスからの呼び出しに対応する `03_personality_profiles.json` および `.yaml` を生成。
- **付属ヘルプドキュメント**：`README.md`、使用例説明 `examples.md`、出荷時テスト検証基準 `tests.md` を作成。

### Changed (変更)
- *なし (初回リリース)*

### Fixed (修正)
- *なし (初回リリース)*
