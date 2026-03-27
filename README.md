# The Edge of Intelligence — AIがあなたのデバイスで動く時代：クラウドの終わりと、エッジの始まり
**The Edge of Intelligence —** <br>
**Why Open-Weight AI Will Move from Cloud to Your Device, and What It Means for Business and Society**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language](https://img.shields.io/badge/Language-English%20%7C%20Japanese-blue)](docs/)

<p align="left">
  <img src="./assets/cover_ogp.png" width="70%">
</p>

*Read this in other languages: [English](README_en.md)*

---

## 📖 概要

2026年1月から2月にかけての8週間で、10の主要なオープンウェイトLLMアーキテクチャが公開された。<br>
GLM-5はGPT-5.2やClaude Opus 4.6と同等のベンチマークスコアを記録し、<br>
Step 3.5 Flashは自身の3倍のサイズを持つDeepSeek V3.2を凌駕した。

**プロプライエタリモデル（GPTやClaudeのように、企業が内部に閉じて開発・提供するAIモデル）と、<br>
オープンウェイトモデル（モデルの中核である学習済みの「重み」が一般に公開され、<br>
誰でもダウンロード・実行できるAIモデル）の性能差は、すでに消滅した。**

この事実が引き起こす構造的な変化は、単なる「モデルの選択肢が増えた」という話にとどまらない。<br>
競争の軸が **「どのモデルが最も賢いか」から「どこで推論を実行し、誰がデータを支配するか」** へ移行する。

本書は、この構造転換を4つの視点から解き明かす。

- **性能収束の証拠** — なぜ、いま、性能差が消えたのか
- **新たな競争軸** — 効率性、速度、オンデバイス、プライバシー
- **企業戦略への影響** — 推論ロケーション・ポートフォリオという新概念
- **消費者行動の不可逆な変化** — サブスク疲れからオンデバイスAIへの不可逆な移行

そして最終章で、これらすべてを著者のDepth & Velocity（D&V）方法論と接続し、<br>
エッジAI時代における新規事業開発の新しい地平を提示する。

---

## 🏗️ 構成

本書は4部構成＋結論で構成される。

### Part 1：The Convergence — 性能格差が「消滅」した構造的証拠

| テーマ | 内容 |
|------|------|
| 2026年春の爆発 | 8週間で10アーキテクチャ。GLM-5、Kimi K2.5、Step 3.5 Flash、Qwen3-Coder-Nextほか |
| ベンチマーク収束 | AI Index、Vectara Hallucination Leaderboard、SWE-Bench Proの3軸で検証 |
| プロプライエタリAPIの残存価値 | 「性能プレミアム」から「信頼性プレミアム」への転換 |
| スケーリング則の民主化 | フロンティア性能は再現可能な工学的成果になった |

### Part 2：The New Battleground — 効率性・速度・オンデバイスという新たな競争軸

| テーマ | 内容 |
|------|------|
| 推論効率（Tokens/sec per Dollar） | Step 3.5 Flashが262kコンテキストで100〜350 tok/sec。11Bアクティブで196Bの知識を維持 |
| オンデバイス実現可能性 | Nanbeige 4.1 3Bはスマートフォン上で動作実証。ワークステーション・ラップトップはすでに実用段階 |
| アーキテクチャ革新 | Mixture-of-Experts（MoE）、Multi-Token Prediction（MTP）、Sliding Window Attention（SWA）、量子化（Quantization）の同時成熟 |
| プライバシーとデータ主権 | 「安全に管理されている」と「そもそも送信されない」の間の、心理的に埋めがたい溝 |

### Part 3：Enterprise Implications — エンタープライズAI戦略を書き換える5つの構造的シフト

| テーマ | 内容 |
|------|------|
| Shift 1 | 「どのモデルか」から「どこで推論するか」へ — データレジデンシー、知財、財務構造を同時に規定 |
| Shift 2 | OpEx（API課金）からCapEx（推論インフラ投資）へ — Lenovo TCO分析：損益分岐点4ヶ月未満、最大18倍のコスト優位 |
| Shift 3 | ベンダーロックインリスクの再評価 — 「許容される必然」から「戦略的怠慢のリスク」へ |
| Shift 4 | 推論ロケーション・ポートフォリオ（Cloud API / On-Premise / Edge の3層設計と動的最適化） |
| Shift 5 | モデル性能からコンテキストエンジニアリングへ — Palantirオントロジーとの構造的一致 |

### Part 4：The Consumer Shift — オンデバイスAIへの不可逆な移行を駆動する5つの力

| テーマ | 内容 |
|------|------|
| 力1：サブスクリプション疲れ | オンデバイスAIの限界費用がゼロであるとき、月額20ドルは「なくても困らない贅沢」に変質する |
| 力2：プライバシーの本能 | 人がAIに聞く最も重要な質問は、最も他者に知られたくない質問だ |
| 力3：レイテンシーの不可逆性 | 即座の応答を体験したユーザーは、クラウドの遅延に戻れない。速度の期待値は一方向にしか動かない |
| 力4：オフライン可用性 | グローバルサウスの数十億人にとって、オンデバイスAIは唯一の選択肢である |
| 力5：所有の感覚 | 「自分のデバイスで動く、自分のAI」という心理的所有感は、TCO計算よりも強力だ |
| フライホイール | 5つの力は相互に強化し合い、すべてが不可逆的に同じ方向に作用する |

### Conclusion：The D&V Perspective on the Edge AI Era

| テーマ | 内容 |
|------|------|
| Depthの再定義 | モデル性能は民主化された。新しいDepthは自社固有のデータ構造化とコンテキストエンジニアリング |
| Velocityの再定義 | 「最新APIの導入速度」から「エッジへの知能展開速度」へ |
| エコシステム接続 | 全6作品のオープンソース知識リポジトリが相互参照する体系 |
| 結語 | 技術が「可能」にし、経済が「合理的」にし、社会が「必要」とする。この移動は、止められない |

---

## 📄 ドキュメント

| ファイル | 言語 | 内容 |
|--------|------|------|
| [Full Text (Japanese)](./docs/ja/the_edge_of_intelligence_jp.md) | 🇯🇵 日本語 | 全文（Part 1〜4 + Conclusion） |
| [Full Text (English)](./docs/en/the_edge_of_intelligence_en.md) | 🇺🇸 English | Full text (Part 1–4 + Conclusion) |

---

## 🔗 Related Projects

本書は、著者のオープンソース知識リポジトリエコシステムの第6の作品として位置づけられる。<br>
それぞれのリポジトリは独立した作品であると同時に、相互に参照し合うことで、AI時代のビジネス戦略の全体像を構成している。

| プロジェクト | 概要 | リンク |
|-------------|------|--------|
| **The AI Strategist** | AIストラテジストという職業を定義し、BTC交差点で戦うための実践的フレームワーク | [GitHub](https://github.com/Leading-AI-IO/the-ai-strategist) |
| **Depth & Velocity** | 生成AI時代の新規事業開発方法論 | [GitHub](https://github.com/Leading-AI-IO/depth-and-velocity) |
| **The Silence of Intelligence** | Anthropic CEO ダリオ・アモディの思想を体系化。産業構造の解剖シリーズ第2弾 | [GitHub](https://github.com/Leading-AI-IO/the-silence-of-intelligence) |
| **The Anatomy of Anthropic** | Anthropicの戦略・製品・研究・安全性を包括的に解剖 | [GitHub](https://github.com/Leading-AI-IO/the-anatomy-of-anthropic) |
| **The Palantir Impact** | Palantir Foundryのオントロジー戦略を解剖。産業構造の解剖シリーズ第1弾 | [GitHub](https://github.com/Leading-AI-IO/palantir-ontology-strategy) |
| **What They Won't Teach You** | AIに有利な世代が教えない、AIの使い方と"思考のOS" | [GitHub](https://github.com/Leading-AI-IO/what-they-wont-teach-you) |
| **The Redesign of Design Strategy** | デザイン戦略の再定義。IDEO崩壊の構造分析を含む | [GitHub](https://github.com/Leading-AI-IO/design-strategy-in-the-ai-era) |
| **The Orchestrator** | AI時代に最も希少な人材像「オーケストレーター」を世界で初めて定義 | [GitHub](https://github.com/Leading-AI-IO/the-orchestrator-in-the-ai-era) |
| **Advertising, Redesigned** | AIが広告を「割り込み」から「優しい提案」に変える。検索の終焉、広告が初めて「歓迎される存在」になる未来。 | [GitHub](https://github.com/Leading-AI-IO/advertising-redesigned) |
| **The AI Organization**             | AI導入が失敗する本質は技術ではなく組織にある。AI時代の組織論      | [GitHub](https://github.com/Leading-AI-IO/the-ai-organization)  |

---

## 👤 著者

**Satoshi Yamauchi** (山内 怜史)<br>
* **Business Designer & AI Strategist at SunAsterisk.inc**
* **Founder / AI Strategist at Leading.AI**
* This project is part of the research by Leading.AI.

* [📒 Read my insights on Note](https://note.com/satoshi_yamauchi)
* [🌐 Visit Leading.AI Official Website](https://www.leading-ai.io/)

---

## 📝 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).<br>
© 2026 Satoshi Yamauchi / Leading AI — Licensed under CC BY 4.0
