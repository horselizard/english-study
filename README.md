# english-study

Claude と一緒に英語を勉強するためのリポジトリです。

## 中身

| パス | 役割 |
|---|---|
| `CLAUDE.md` | Claude への指示と、学習者プロフィール(レベル・目標) |
| `.claude/skills/socratic/SKILL.md` | ソクラテス式の問いかけスキル |
| `notes/mistakes.md` | 間違いノート。復習クイズの出題元 |
| `notes/vocabulary.md` | 単語・表現ノート |

## 使い方

このリポジトリを選んで Claude Code のセッションを始め、ふつうに話しかけます。

- `/socratic 現在完了と過去形の違い` — 問いかけ形式で理解を深める
- `/socratic この英文を添削して: I go to shopping yesterday.` — 自分で直せるようにヒントをもらう
- `/socratic 復習` — 間違いノートからクイズ
- `resilient ってどういう意味?` — 意味だけ知りたいときは、そのまま聞けばすぐ答えが返る

問答の途中で「答え教えて」と言えば、すぐ答えに切り替わります。

## 調整したいとき

- レベルや目標が変わったら `CLAUDE.md` のプロフィールを書き換える
- 問いかけの厳しさや進め方を変えたいときは `.claude/skills/socratic/SKILL.md` を編集する(日本語で書いてあります)
