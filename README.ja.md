<h1 align="center">白石 拓海 (Takumi Shiraishi)</h1>

<p align="center">
  <a href="https://wovol.com">Wovol</a> 代表・エンジニア。<br>
  ローカルファーストな AI プロダクト、根拠にリンクが張られた開発者ツール、そして出荷を可能にする地味な安全側の作業。
</p>

<p align="center">
  <a href="README.md">English</a> &nbsp;·&nbsp; <b>日本語</b>
</p>

<p align="center">
  <a href="https://wovol.com"><img alt="wovol.com" src="https://img.shields.io/badge/wovol.com-000000?style=flat-square&logo=vercel&logoColor=white"></a>
  <a href="mailto:takumi@wovol.com"><img alt="Email" src="https://img.shields.io/badge/takumi@wovol.com-24292F?style=flat-square&logo=gmail&logoColor=white"></a>
  <img alt="拠点" src="https://img.shields.io/badge/Japan%20%2F%20Vancouver%2C%20BC-3B7DD8?style=flat-square&logo=googlemaps&logoColor=white">
</p>

---

## いま作っているもの

- **vajco ai** (private) — macOS 向けの先回りワークスペース層。ホットキーを押すと、次に再開しようとしていたものがすでに準備されている。リポジトリ、ブランチ、開いていたタブ、cwd、そしてオンデバイス生成の一行要約。Swift 6 / SwiftUI、ソース約 240 ファイル、notarized `0.1.0` ビルド。[ランディングページ →](https://wovol.com/lp/vajco-ai)
- **Sonae** (private) — 市民ひとりに一体のパーソナル防災エージェント。単一の AMD Instinct MI300X 上で 8,000 体が並列に推論する。[ライブデモ →](https://sonae-visitor-lp.vercel.app/) · [プロジェクト紹介 →](https://lablab.ai/ai-hackathons/amd-developer/sonae/sonae-personal-disaster-ai-agent-for-each-citizen)
- **LegacyLens** (private) — Java/Spring レガシーコードの理解を支援するセルフホスト型ツール。根拠行にリンクした HTML/PDF レポートと機械可読な `evidence.json` を出力する。マネージドバックエンドを持たず、顧客の端末内で完結する。
- 今週は **iOSDC Japan 2026** に参加中。会場で見かけたら声をかけてください。

## 主な仕事

| プロジェクト | 内容 | 技術 | 種別 | リンク |
| --- | --- | --- | --- | --- |
| **vajco ai** | macOS の先回りワークスペース層。すべてオンデバイスで、データは端末外に出ない。 | Swift 6, SwiftUI, GRDB/SQLite, Apple FoundationModels, Accessibility API | 🔒 Private | [ランディングページ](https://wovol.com/lp/vajco-ai) |
| **Sonae** | 市民単位の防災エージェント。台風 → 洪水 → 停電 → 通信途絶という災害の連鎖を、個別の事象ではなく一本の鎖として追跡する。AMD Developer Cloud Hackathon 2026 Track 3 向けに構築。 | Next.js, FastAPI, vLLM, ROCm, Qwen3.5-122B-A10B-FP8, Leaflet | 🔒 Private | [デモ](https://sonae-visitor-lp.vercel.app/) · [lablab.ai](https://lablab.ai/ai-hackathons/amd-developer/sonae/sonae-personal-disaster-ai-agent-for-each-citizen) |
| **LegacyLens** | 日本の SIer 向け Java/Spring レガシー監査ツール。レポート内のすべての記述が、根拠となるソース行へ遡れる。 | TypeScript, Node, pnpm, Docker, JSON Schema | 🔒 Private | — |
| **Axiom** | 楽しさ優先・プライバシー優先の AI 学習コーチ。既定でサードパーティ計測を入れない。 | React 19, Vite, Tailwind v4, shadcn/ui, Three.js, KaTeX, Zod | 🔒 Private (Wovol モノレポ内) | [axiom.wovol.com](https://axiom.wovol.com) |
| **Lumen** | コードの *表現形式* がフロンティア LLM のコード推論精度を変えるかを検証した実証研究。情報量を揃える対照条件 (C1+) を設計。事前登録あり、9 セルの確証実験を Holm 補正。結果は 9 セルすべてで非棄却。 | Python, LaTeX | 🌐 **Public** | [リポジトリ](https://github.com/WhiteStoneTak/Lumen) · [preprint-v1](https://github.com/WhiteStoneTak/Lumen/releases/tag/preprint-v1) · [/research](https://wovol.com/research) |
| **SEO** | サイトにコミット権を持つ人のための SEO 実務手順。散文、チェックリスト、エージェント用プレイブック。クローラもスコアリングエンジンも持たない。 | Markdown, agent skills | 🌐 **Public** | [リポジトリ](https://github.com/WhiteStoneTak/SEO) |
| **4-bit Binary Calculator** | ビー玉式論理ゲート (XOR / AND / OR と自作の Y 分岐ゲート) で組んだ機械式 4bit 計算機。レーザーカットの 2D MDF。真理値表つきの検証パックと、失敗した試作も公開している。 | CAD (DWG), HTML デモ | 🌐 **Public** | [リポジトリ](https://github.com/WhiteStoneTak/4-bit-Binary-Calculator) |
| **wovol-lab** | ローカル完結の Claude Code 運用ラボ。神経科学に着想を得た記憶層 (mnemos)、4 プロファイルのブラウザ分離、そして全書き込みを 30 以上の PII / シークレットパターンで走査する日英両対応の安全網。自動送信は行わない。 | Python, shell hooks | 🔒 Private | — |

> 🔒 private リポジトリも載せているのは、実際の作業の大半がそこで起きているため。上のリンクは本当に公開されている部分 (デモ、ランディングページ、紹介記事) に限っている。

## オープンソースと上流への貢献

- [**home-assistant/core#181366**](https://github.com/home-assistant/core/pull/181366) — `tesla_fleet` 統合に対して、読み取り専用の最小権限 OAuth スコープを提案 (9 ファイル、+632 / −60)。統合のコードオーナーとの議論を経てクローズ。既存の同意フローでもユーザーがコマンド系スコープを外せる、という指摘を受けたため。公開リポジトリであり、マージされるよりレビュースレッド自体に価値があった。
- **EasyDialog / homepage** (private の顧客リポジトリ) — 2026 年 8 月から 9 月にかけて本番へ 8 件の PR をマージ。HTTP から HTTPS へのリダイレクトと最小構成の CSP、ルート / `robots.txt` / `sitemap.xml` の正規レスポンス、ロケール対応メタデータと言語属性、main ランドマーク・スキップリンク・アクセシブルなナビゲーション、リンク先への参照元とサーチクレジットを遮断していた referrer ポリシーの修正、セキュリティと CI の基礎的な強化。
- 公開している成果物は上表の **Lumen**、**SEO**、**4-bit-Binary-Calculator**。いずれも証拠ファーストで書いてある。手法、データ、そして失敗した反復まで残している。

## ハイライト

- **paiza S ランク (Python)。** paiza スキルチェックの最上位ランク。
- **Lumen のプレプリントを凍結してタグ付け。** 確証実験の前に事前登録を書き、9 セルに Holm 補正をかけ、ヌル結果をヌルとして報告した。
- **セキュリティは工程ではなく既定値。** リポジトリ全体のシークレット走査 (git 履歴を含む)、ビルド時の CSP ハッシュ生成、専用のセキュリティ CI ワークフロー、そして欧米圏の識別子に加えて日本固有の情報 (マイナンバー / 保険証 / 戸籍) も対象にした PII パターン照合。
- **最初から二言語で作る。** 日本語ネイティブ、英語も実務レベル。プロダクト文言もセキュリティツールも顧客向け文書も、両方の言語で出す。

## 技術スタック

**言語**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-437291?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Web**

![React](https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

**Apple プラットフォーム**

![Swift 6](https://img.shields.io/badge/Swift%206-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=flat-square&logo=swift&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)
![SwiftPM](https://img.shields.io/badge/SwiftPM-FA7343?style=flat-square&logo=swift&logoColor=white)
![macOS](https://img.shields.io/badge/macOS%2026+-000000?style=flat-square&logo=apple&logoColor=white)

**バックエンドとデータ**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js%2022-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite%20%2F%20GRDB-003B57?style=flat-square&logo=sqlite&logoColor=white)

**AI と推論基盤**

![Anthropic](https://img.shields.io/badge/Claude%20%2F%20MCP-D97757?style=flat-square&logo=anthropic&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FDB515?style=flat-square&logo=huggingface&logoColor=black)
![ROCm](https://img.shields.io/badge/AMD%20ROCm-ED1C24?style=flat-square&logo=amd&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen3.5-615CED?style=flat-square&logo=huggingface&logoColor=white)
![FoundationModels](https://img.shields.io/badge/Apple%20FoundationModels-000000?style=flat-square&logo=apple&logoColor=white)

**ビルドと運用**

![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)

## GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=WhiteStoneTak&theme=github_dark">
    <img height="200" alt="WhiteStoneTak の GitHub プロフィール概要" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=WhiteStoneTak&theme=github">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=WhiteStoneTak&theme=dark&hide_border=true&card_width=700&card_height=200">
    <img height="200" alt="コントリビューション連続日数" src="https://streak-stats.demolab.com?user=WhiteStoneTak&theme=default&hide_border=true&card_width=700&card_height=200">
  </picture>
</p>

<p align="center"><sub>コミットの大半は private リポジトリにあるため、公開リポジトリだけを集計した言語比率は実態より小さく出る。正確な内訳は上の表のほう。</sub></p>

## 連絡先

**メール:** [takumi@wovol.com](mailto:takumi@wovol.com) &nbsp;·&nbsp; **Web:** [wovol.com](https://wovol.com)

ローカルファースト AI、Apple プラットフォーム、レガシーシステム向け開発者ツール、そして手元で検証できる証拠を伴う話題であれば歓迎します。
