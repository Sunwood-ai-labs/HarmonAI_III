<h1 align="center">HarmonAI III 🌟</h1>

<p align="center">
  <img src="https://huggingface.co/datasets/MakiAi/IconAssets/resolve/main/HarmonAI_III_icon.jpeg" width="100%">
</p>

<p align="center">
  <a href="https://github.com/Sunwood-ai-labs/HarmonAI_III">
    <img alt="GitHub Repo" src="https://img.shields.io/badge/github-HarmonAI__III-blue?logo=github">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/HarmonAI_III/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/Sunwood-ai-labs/HarmonAI_III?color=green">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/HarmonAI_III/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/Sunwood-ai-labs/HarmonAI_III?style=social">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/HarmonAI_III/releases">
    <img alt="GitHub release" src="https://img.shields.io/github/v/release/Sunwood-ai-labs/HarmonAI_III?include_prereleases&style=flat-square">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/HarmonAI_III/graphs/commit-activity">
    <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/Sunwood-ai-labs/HarmonAI_III">
  </a>
  <a href="https://github.com/Sunwood-ai-labs/HarmonAI_III/pulls">
    <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square">
  </a>
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Sunwood-ai-labs/HarmonAI_III">
  <img alt="Development Status" src="https://img.shields.io/badge/status-active-success.svg">
</p>

<h2 align="center">
  ～AI開発の新時代へ、無限の可能性を秘めて～
</h2>

> [!IMPORTANT]
> このリポジトリは、AIアシスタントを活用して開発されています。リリースノート、README、コミットメッセージの大部分は、最新のAI技術を用いて生成されています。

## 🌟 HarmonAI IIIへようこそ！

HarmonAI IIIは、次世代のAI開発のための**テンプレートリポジトリ**です。大規模言語モデル（LLM）とマルチモーダルLLMの事前学習、ファインチューニング、デプロイメントを包括的にサポートするための基盤を提供します。HarmonAI IIとLLaMA2-Accessoryの優れた特徴を融合し、より高度で柔軟なAI開発環境のテンプレートを実現しています。

## 🚀 HarmonAI IIIの特長

### 1. 多様なデータセットとタスクのサポート
- 🎯 RefinedWebやStarCoderを使用した事前学習のテンプレート
- 📚 Alpaca、ShareGPT、LIMA、WizardLM、Flacuna、Platypus、UltraChat、MOSSなどを用いた単一モーダルファインチューニングの例
- 🌈 LAION、COYO、MMC4、OBELISC、LLaVA、Shrika、Bardなどを活用したマルチモーダルファインチューニングのサンプル
- 🔧 GPT4ToolsやGorillaを用いたAPI制御のためのLLM実装例

### 2. 効率的な最適化とデプロイメントのテンプレート
- 🚝 Zero-init AttentionやBias-norm Tuningによるパラメータ効率の良いファインチューニングの実装例
- 💻 Fully Sharded Data Parallel (FSDP)、Flash Attention 2、QLoRAのサポート方法

### 3. 多様な視覚エンコーダーとLLMのサポート例
- 👁‍🗨 CLIP、Q-Former、ImageBind、DINOv2などの視覚エンコーダーの統合方法
- 🧩 LLaMA、LLaMA2、CodeLlama、InternLM、Falcon、Mixtral-8x7Bなどのサポート例

### 4. 柔軟なカスタマイズと拡張性のためのガイドライン
- 🛠️ モジュール化された設計により、新しいモデルや手法の追加が容易になるテンプレート構造
- 🔧 設定ファイルを通じた簡単なプロジェクトカスタマイズの方法

### 5. 包括的なドキュメンテーションとサポートの例
- 📚 詳細なセットアップガイドと使用方法の説明テンプレート
- 🤝 活発なコミュニティとサポート体制の構築ガイドライン

## 📂 リポジトリ構成

HarmonAI IIIは、以下のような構成を持つテンプレートリポジトリです：

```
HarmonAI_III/
├── src/                  # ソースコードのテンプレート
├── tests/                # テストコードの例
├── docs/                 # ドキュメントのサンプル
├── examples/             # 使用例とサンプルスクリプト
├── config/               # 設定ファイルのテンプレート
├── scripts/              # ユーティリティスクリプト
├── .github/              # GitHub Actions等の設定
├── LICENSE               # ライセンスファイル
└── README.md             # プロジェクト概要（本ファイル）
```

この構成は、AI開発プロジェクトの一般的な要件に基づいて設計されていますが、各プロジェクトのニーズに応じてカスタマイズすることができます。

## 🛠️ セットアップ

環境のセットアップについては、[インストールガイド](https://llama2-accessory.readthedocs.io/en/latest/install.html)を参照してください。

```bash
git clone https://github.com/Sunwood-ai-labs/HarmonAI_III.git
cd HarmonAI_III
pip install -r requirements.txt
```

## 📚 使用方法

HarmonAI IIIの使用方法に関する詳細な情報は、[ドキュメント](https://harmonai-iii.readthedocs.io)を参照してください。以下は基本的な使用例です：

```python
from harmonai_iii import HarmonAI

model = HarmonAI.load("path/to/model")
output = model.generate("こんにちは、世界！")
print(output)
```

## 🤝 コントリビューション

HarmonAI IIIは、オープンソースプロジェクトとしてコミュニティからの貢献を歓迎しています。バグ報告、機能リクエスト、プルリクエストなどを通じて、このテンプレートリポジトリの改善にご協力ください。

## 📄 ライセンス

HarmonAI IIIは、[MITライセンス](LICENSE)の下で公開されています。

## 🙏 謝辞

HarmonAI IIIの開発にあたり、[LLaMA-Adapter](https://github.com/OpenGVLab/LLaMA-Adapter)、[LLaMA2-Accessory](https://github.com/Alpha-VLLM/LLaMA2-Accessory)、そして多くのオープンソースプロジェクトに感謝いたします。

---

HarmonAI IIIは、AIと人間の調和を目指し、開発者の皆様に最高のAI開発テンプレートを提供できるよう尽力してまいります。ぜひ、HarmonAI IIIを活用し、革新的なAIプロジェクトの基盤として役立ててください！
