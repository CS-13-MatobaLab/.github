# Welcome to Matoba Lab (CS-13) 👋

神戸大学 システム情報学研究科 的場研究室 (CS-13) の公式GitHub組織アカウントです。
ここでは研究室内のソースコード管理、共同開発を行っています。

## 🔰 Git初心者の方へ (For Beginners)
この研究室ではコード管理に **Git (ギット)** を使用します。
最初は難しく感じるかもしれませんが、以下の「3つの基本動作」だけ覚えれば研究は進められます。

1. **Clone (クローン)**: GitHubにあるコードを自分のPCにコピーすること（最初の1回だけ）。
2. **Pull (プル)**: 誰かが更新した最新のコードを自分のPCに取り込むこと（実験前に毎回やる）。
3. **Push (プッシュ)**: 自分が書いたコードをGitHubにアップロードすること（帰る前にやる）。

---

## 🔬 研究チーム (Research Teams)

| チーム名 | 研究テーマ |
| :--- | :--- |
| **[Holography](https://github.com/orgs/CS-13-MatobaLab/teams/holography)** | ホログラフィック顕微鏡, DHM, 位相計測 |
| **[Scattering](https://github.com/orgs/CS-13-MatobaLab/teams/scattering)** | 散乱透視, Wavefront Shaping, NLOS |
| **[Quantum](https://github.com/orgs/CS-13-MatobaLab/teams/quantum)** | 量子イメージング, 量子光学 |
| **[Computational](https://github.com/orgs/CS-13-MatobaLab/teams/computational)** | 計算機イメージング, アルゴリズム開発 |

---

## 🚨 絶対に守るルール (Rules)

### ⚠️ 実験データはアップロード禁止
Gitは「テキスト（プログラム）」を保存する場所です。
**画像(`bmp, tiff`)、動画(`mp4`)、巨大な解析データ(`mat, csv`)** は絶対にアップロードしないでください。
* なぜ？ → リポジトリが数GBになると、全員の同期が遅くなり、破損の原因になります。
* 対策 → `.gitignore` ファイルで除外設定されているか確認してください。

### 🔄 作業の流れ
1. **Pull**: 作業を始める前に `git pull` で最新にする。
2. **Branch**: なるべく `main` を直接触らず、作業用ブランチを作る（慣れてきたらでOK）。
3. **Commit**: こまめに保存する（「〇〇のバグ修正」など分かりやすいメッセージで）。

---

## 📖 困ったときのコマンド集 (Cheat Sheet)

ターミナル（PowerShellやMacのTerminal）で使う基本コマンドです。

| したいこと | コマンド | 解説 |
| :--- | :--- | :--- |
| **最初に持ってくる** | `git clone [URL]` | リポジトリをダウンロードします |
| **最新にする** | `git pull` | サーバーの更新を取り込みます |
| **変更を登録する** | `git add .` | 変更した全ファイルを送る準備をします |
| **記録する** | `git commit -m "修正内容"` | メッセージ付きで保存します |
| **アップロード** | `git push` | GitHubに送信します |
| **状態確認** | `git status` | 変更されたファイルを確認します |

---

