# 🌟 HarmonAI III 🌟

<p align="center">
  <img src="./docs/HarmonAI-III.png" width="100%">
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
  ～ AI-Powered Automated Repository Management Template ～
</h2>

> [!IMPORTANT]
> HarmonAI III is a template repository developed using [cline (formerly Claude Dev)](https://github.com/clinebot/cline) and [SourceSage](https://github.com/Sunwood-ai-labs/SourceSage).  A large portion of the release notes, README, and commit messages were generated using the latest AI technology.

## 🚀 Project Overview

HarmonAI III is an innovative **AI repository starter kit** integrating AIRA and IRIS. This repository aims to dramatically improve developer efficiency by providing a structure and workflow for LLM-powered AI development projects. Version: `v1.0.0`


## 📅 Update Information

- 🎉 【2024-10-11】 : **HarmonAI III** [Release v1.0.0](https://github.com/Sunwood-ai-labs/HarmonAI_III/releases/tag/v1.0.0) Project launched

## ✨ Key Features

1. **Integrated AI Toolset**: Provides the functionality of AIRA and IRIS in a single package.
2. **Ready to Use**: Easily create a repository with a high-quality initial structure by using it as a template.
3. **Automated Development Workflow**: Automates commit message generation, release note creation, and issue management.
4. **Multilingual Support**: Supports international project deployment through automated README translation.
5. **Flexible Customization**: Easily adaptable to the needs of your project.

## 🛠️ How to Use

### AIRA Example:
```bash
aira --mode sourcesage commit  --config=.aira\config.dev.commit.yml --ss-model-name="gpt-4o-mini" --llm-output="llm_output.md"
```

### IRIS Example:

Refer to the documentation for each component for detailed usage instructions.


## 📦 Installation Instructions

1. Use this repository as a template to create a new repository.
2. Clone the repository locally.
3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Customize the AIRA and IRIS configuration files.
5. Check the GitHub Actions settings and configure environment variables as needed.
6. Open the `.github/release_notes/.sourcesage_releasenotes_iris.yml` file and change the value of `repo-name:` to your new repository name.


## 🌿 Environment Setup

To set up the HarmonAI III environment, follow these steps:

1. Create a virtual environment:
   ```bash
   python3 -m venv .venv
   ```
   This will create a virtual environment in the `.venv` directory.

2. Activate the virtual environment:
   ```bash
   source .venv/bin/activate  # Linux/macOS
   .venv\Scripts\activate  # Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

These steps will prepare the development environment for HarmonAI III.


## 📚 Main Components

### 🤖 [AIRA (AI-Integrated Repository for Accelerated Development)](https://github.com/Sunwood-ai-labs/AIRA)
- Automated repository creation
- Automated commit message generation

### 🌈 [IRIS (Intelligent Repository Issue Solver)](https://github.com/Sunwood-ai-labs/IRIS)
- Automated issue classification
- Automated solution suggestions
- Automated release note generation
- Automated README translation


## 🐈 Process Flow


```mermaid
%%{init:{'theme':'base','themeVariables':{'primaryColor':'#024959','primaryTextColor':'#F2C335','primaryBorderColor':'#F2AE30','lineColor':'#A1A2A6','secondaryColor':'#593E25','tertiaryColor':'#F2C335','noteTextColor':'#024959','noteBkgColor':'#F2C335','textColor':'#024959','fontSize':'18px'}}}%%

graph LR
    A[Start] --> B[Repository Conception and Naming]
    B -->|Human-performed| C[HarmonAI III Repository Initialization]
    C -->|Automated| D[Development Work]
    D -->|Human-performed| E[AIRA Automated Commits]
    E --> H[IRIS Release Note Creation]
    H --> I[IRIS Documentation Translation]
    I --> J[Release]
    J --> K[End]

    class B,D,G human;
    class E aira;
    class F,H,I iris;
    class C auto;
    class A,J,K process;

```


## 🤝 Contributions

HarmonAI III welcomes contributions from the community as an open-source project. Please help improve this template repository through bug reports, feature requests, and pull requests.

## 📄 License

HarmonAI III is released under the [MIT License](LICENSE).

## 🙏 Acknowledgements

HarmonAI III draws inspiration from many open-source projects.  We especially thank the developers of AIRA and IRIS.  Thanks also to Maki.

---

HarmonAI III is an excellent starter kit for achieving an AI-driven development process. Let's start developing innovative AI projects based on this template!