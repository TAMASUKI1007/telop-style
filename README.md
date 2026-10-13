# telop-style

CapCut で作ったテニスレッスン動画（縦型）のテロップの決まりごとをまとめたリポジトリ。

- **[telop-style.md](telop-style.md)** … テロップのスタイルガイド（本体）
- **[CLAUDE.md](CLAUDE.md)** … Claude への指示（テロップを入れるときは必ず telop-style.md を読む）
- **drafts/** … 分析に使った CapCut プロジェクト5本の draft_content.json（動画・画像は含まない）

## 別の PC で使う手順

1. 公開リポジトリなので GitHub へのログインは不要（Git だけ入っていればよい）
2. 好きな場所でターミナルを開いて取り込む
   ```bash
   git clone https://github.com/TAMASUKI1007/telop-style.git
   ```
3. Claude Code（デスクトップアプリの Code タブ）で、取り込んだ `telop-style` フォルダを開く
4. 「テロップを入れて」と頼むと、CLAUDE.md の指示で telop-style.md が読まれる
5. 最初の1本は、元の動画と見比べて色・大きさ・位置がずれていないか確認する。ずれていたら telop-style.md を直してコミットする

更新を取り込むときは、フォルダ内で `git pull`。
