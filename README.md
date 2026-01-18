# michel-mayonaka

AI駆動の開発ツールやコンテンツ生成に興味があります。

## Projects

### FFmpegショート動画自動生成

ChatGPTと連携したショート動画の自動生成スクリプトを作成しました。

- **台本生成**: OpenAI GPT-4oモデルでTSV形式の台本を生成
- **画像生成**: 台本から画像プロンプトを生成し、gpt-image-1で画像を生成
- **音声生成**: VOICEVOXで音声を生成
- **動画合成**: FFmpegで画像・音声を合成して動画を生成

生成した動画: [ディストピア弁当 - YouTube](https://www.youtube.com/@ディストピア弁当)

---

### oneshot-agent

GitHub Issue駆動のエージェントハーネス（Codex CLI版）

https://github.com/michel-mayonaka/oneshot-agent

- Codex CLIをプランニングモードで起動し、対話的にプランニングを実施
- 承認後、`gh`コマンドでGitHub Issueを自動登録
- GitHub Issueをもとに、実装からPR発行までを自動実行
- branch/worktreeの発行もコマンド内で自動化
- Issue単位でスクリプトログ・エージェント実装ログを保存

---

### claude-issue-flow

GitHub Issue駆動のエージェントハーネス（Claude Agent SDK版）

https://github.com/michel-mayonaka/claude-issue-flow

---

## GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=michel-mayonaka&show_icons=true&theme=default)

