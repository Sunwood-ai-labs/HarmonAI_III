# HarmonAI III 🌟

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
</p>

<h2 align="center">
  ～AI開発の新時代へ、無限の可能性を秘めて～
</h2>

> [!IMPORTANT]
> このリポジトリは、AIアシスタントを活用して開発されています。リリースノート、README、コミットメッセージの大部分は、最新のAI技術を用いて生成されています。

## 🌟 HarmonAI IIIへようこそ！

HarmonAI IIIは、次世代のAI開発のためのオープンソーステンプレートリポジトリです。大規模言語モデル（LLM）とマルチモーダルLLMの事前学習、ファインチューニング、デプロイメントを包括的にサポートします。HarmonAI IIとLLaMA2-Accessoryの優れた特徴を融合し、より高度で柔軟なAI開発環境を提供します。

## 🚀 HarmonAI IIIの特長

### 1. 多様なデータセットとタスクのサポート
- 🎯 RefinedWebやStarCoderを使用した事前学習
- 📚 Alpaca、ShareGPT、LIMA、WizardLM、Flacuna、Platypus、UltraChat、MOSSなどを用いた単一モーダルファインチューニング
- 🌈 LAION、COYO、MMC4、OBELISC、LLaVA、Shrika、Bardなどを活用したマルチモーダルファインチューニング
- 🔧 GPT4ToolsやGorillaを用いたAPI制御のためのLLM

### 2. 効率的な最適化とデプロイメント
- 🚝 Zero-init AttentionやBias-norm Tuningによるパラメータ効率の良いファインチューニング
- 💻 Fully Sharded Data Parallel (FSDP)、Flash Attention 2、QLoRAのサポート

### 3. 多様な視覚エンコーダーとLLMのサポート
- 👁‍🗨 CLIP、Q-Former、ImageBind、DINOv2などの視覚エンコーダー
- 🧩 LLaMA、LLaMA2、CodeLlama、InternLM、Falcon、Mixtral-8x7Bなどのサポート

### 4. 柔軟なカスタマイズと拡張性
- 🛠️ モジュール化された設計により、新しいモデルや手法の追加が容易
- 🔧 設定ファイルを通じた簡単なプロジェクトカスタマイズ

### 5. 包括的なドキュメンテーションとサポート
- 📚 詳細なセットアップガイドと使用方法の説明
- 🤝 活発なコミュニティとサポート体制

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

HarmonAI IIIは、オープンソースプロジェクトとしてコミュニティからの貢献を歓迎しています。バグ報告、機能リクエスト、プルリクエストなどを通じて、プロジェクトの改善にご協力ください。

## 📄 ライセンス

HarmonAI IIIは、[MITライセンス](LICENSE)の下で公開されています。

## 🙏 謝辞

HarmonAI IIIの開発にあたり、[LLaMA-Adapter](https://github.com/OpenGVLab/LLaMA-Adapter)、[LLaMA2-Accessory](https://github.com/Alpha-VLLM/LLaMA2-Accessory)、そして多くのオープンソースプロジェクトに感謝いたします。

---

HarmonAI IIIは、AIと人間の調和を目指し、開発者の皆様に最高のエクスペリエンスを提供できるよう尽力してまいります。ぜひ、HarmonAI IIIを活用し、AIの力を開発に役立ててください！
