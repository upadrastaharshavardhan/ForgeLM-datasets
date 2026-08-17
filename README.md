# 🧬 ForgeLM-Datasets
<img width="1983" height="793" alt="image" src="https://github.com/user-attachments/assets/e3bdd281-90ed-446f-9e9b-5243cb47ee8f" />

<p align="center">

# ForgeLM Datasets

### 🔥 Build Your Own LLM Training Dataset

**A curated collection of open datasets for instruction tuning, SFT, RLHF, reasoning, coding, multilingual AI, safety, function calling, multimodal learning, and conversational AI.**

<p align="center">

[![Datasets](https://img.shields.io/badge/Datasets-100%2B-blue?style=for-the-badge)](#-dataset-catalog)
[![Languages](https://img.shields.io/badge/Languages-Multilingual-purple?style=for-the-badge)](#-language-coverage)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Datasets-yellow?style=for-the-badge)](https://huggingface.co/datasets)
[![GitHub](https://img.shields.io/badge/GitHub-ForgeLM-black?style=for-the-badge)](https://github.com/upadrastaharshavardhan)
[![License](https://img.shields.io/badge/License-Varies-orange?style=for-the-badge)](#-license--usage)

</p>

</p>

---

## 🚀 What Is ForgeLM-Datasets?

**ForgeLM-Datasets** is a curated dataset collection designed to help researchers, developers, students, and AI engineers quickly discover and assemble datasets for building their own Large Language Models and specialized AI systems.

Instead of searching across dozens of repositories individually, this project provides a centralized catalog of datasets covering:

* 🧠 Instruction tuning
* 💬 Conversational AI
* 💻 Code generation
* 🧮 Mathematical reasoning
* 🔬 Scientific reasoning
* 🛡️ AI safety
* 🔧 Function calling
* 🤖 Agentic AI
* 🌍 Multilingual training
* 👁️ Vision-language learning
* 🎯 Preference optimization
* 🧪 Evaluation
* 📚 Knowledge-intensive QA
* 🧩 Long-context and long-form generation

The goal is simple:

> **Discover → Select → Merge → Preprocess → Upload → Train**

---

# 🗺️ Quick Start

## 1️⃣ Clone the Dataset Repository

```bash
git clone https://github.com/upadrastaharshavardhan/ForgeLM-datasets
```

## 2️⃣ Navigate to the Mixed Dataset Collection

```bash
cd ForgeLM-datasets/mixed/dataset
```

## 3️⃣ Select Your Dataset

Choose any dataset that matches your training objective.

Examples:

```text
Instruction Tuning
├── Alpaca
├── Dolly
├── Self-Instruct
└── WizardLM

Reasoning
├── NaturalReasoning
├── OpenR1-Math
├── TheoremQA
└── GSM-IC

Code
├── CodeAlpaca
├── CodeParrot
└── Function Calling datasets

Safety
├── WildGuardMix
├── WildJailbreak
├── SafeRLHF
└── ProsocialDialog
```

## 4️⃣ Preprocess and Upload

```bash
python preprocess.py your_dataset_name_to_HuggingFaceHub
```

This allows you to prepare the selected dataset for your own training pipeline.

---

# 🧠 Dataset Selection Strategy

Different models require different types of training data.

### General-Purpose LLM

Recommended combination:

```text
Instruction Data
        +
Conversation Data
        +
Knowledge QA
        +
Reasoning
        +
Preference Data
```

### Coding LLM

```text
Code Generation
        +
Code Instruction
        +
Function Calling
        +
Tool Usage
        +
Reasoning
```

### Agentic LLM

```text
Instruction Following
        +
Function Calling
        +
Tool Planning
        +
Multi-Turn Conversation
        +
Reasoning
```

### Safety-Aligned LLM

```text
SafeRLHF
    +
WildGuard
    +
WildJailbreak
    +
Prosocial Dialog
    +
Preference Data
```

---

# 📊 Dataset Catalog

The catalog is organized approximately from **smaller datasets to larger datasets**. Dataset sizes are based on the source information included in this project.

## 🔹 Small → Medium Datasets

| Dataset                      | Size | Language       | Primary Use                         |
| ---------------------------- | ---: | -------------- | ----------------------------------- |
| TheoremQA                    |   1K | English        | Mathematical / scientific reasoning |
| LIMA                         |   1K | English        | Alignment                           |
| WildGuardMix                 | 1.7K | English        | AI safety                           |
| BFCL                         |   2K | English + Code | Function calling                    |
| im-feeling-curious           |   3K | English        | Knowledge                           |
| Puffin                       |   3K | English        | Multi-turn conversation             |
| cc_sbu_align                 |   4K | English        | Image-text alignment                |
| QA-Feedback                  |   4K | English        | QA + feedback                       |
| SLF5K                        |   5K | English        | Summarization                       |
| blended_skill_talk           |   7K | English        | Conversation                        |
| GSM-IC                       |   8K | English        | Mathematics                         |
| ChatAlpaca-10K               |  10K | English        | Instruction following               |
| PKU-SafeRLHF-10K             |  10K | English        | Safety / preference                 |
| Dolly-15K                    |  15K | English        | Instruction tuning                  |
| WebGPT Comparisons           |  20K | English        | Preference learning                 |
| CodeAlpaca-20K               |  20K | English        | Code generation                     |
| HelpSteer2                   |  21K | English        | Helpfulness                         |
| OpenAPI Function Invocations |  25K | English        | Tool calling                        |
| LongForm                     |  28K | English        | Long-form generation                |

---

# 🔹 Medium-Scale Datasets

| Dataset                     | Size | Language          | Primary Use                  |
| --------------------------- | ---: | ----------------- | ---------------------------- |
| Chatbot Arena Conversations |  33K | English           | Preference / conversations   |
| HC3                         |  37K | English + Chinese | Human vs LLM detection       |
| Anthropic HH Golden         |  45K | English           | Helpful / harmless alignment |
| Mol-Instructions            |  48K | English           | Biology / scientific AI      |
| RefGPT                      |  50K | English + Chinese | Referenced Q&A               |
| arXiv Math Instruct         | 50K+ | English           | Mathematical instruction     |
| Traditional Chinese Alpaca  |  52K | Chinese           | Instruction tuning           |
| Cabrita Dataset             |  52K | Portuguese        | Multilingual instruction     |
| Japanese Alpaca             |  52K | Japanese          | Instruction tuning           |
| Alpaca                      |  52K | English           | Instruction tuning           |
| Alpaca Cleaned              |  52K | English           | Instruction tuning           |
| Alpaca GPT-4                |  52K | English           | Instruction tuning           |
| Alpaca GPT-4 Chinese        |  52K | Chinese           | Instruction tuning           |
| xLAM Function Calling       |  60K | English           | Tool calling                 |
| Dynosaur                    |  66K | English           | Instruction curation         |
| Finance                     |  69K | English           | Financial AI                 |
| WizardLM Evol-Instruct      |  70K | English           | Instruction evolution        |
| Vicuna                      |  75K | English           | Conversational AI            |
| InstructionTranslation      |  80K | Multilingual      | Translation                  |
| Self-Instruct               |  82K | English           | Instruction generation       |
| OASST1                      |  89K | Multilingual      | Assistant conversations      |
| HH-RLHF                     |  91K | English           | Preference alignment         |
| Guanaco                     |  98K | Multilingual      | Instruction tuning           |

---

# 🔹 Large Datasets

| Dataset                   | Size | Language          | Primary Use                 |
| ------------------------- | ---: | ----------------- | --------------------------- |
| InstructionWild           | 104K | English + Chinese | Instruction generation      |
| CAMEL                     | 107K | English           | Multi-role dialogue         |
| TAPIR-Cleaned             | 117K | English           | Instruction following       |
| OASST2                    | 135K | Multilingual      | Assistant conversations     |
| WizardLM Evol-Instruct V2 | 143K | English           | Instruction evolution       |
| LLaVA Visual Instruct     | 150K | English           | Multimodal AI               |
| ProsocialDialog           | 166K | English           | Safety                      |
| M2Lingual                 | 175K | Multilingual      | Multimodal / code           |
| COIG                      | 191K | Chinese           | Instruction tuning          |
| OpenOrca                  | 198K | English           | Conversational AI           |
| OpenR1-Math               | 220K | English           | Mathematical reasoning      |
| Unnatural Instructions    | 241K | English           | Instruction generation      |
| WildJailbreak             | 262K | English           | Safety / jailbreak research |
| SHP                       | 358K | English           | Preference learning         |
| Dromedary                 | 361K | English           | Instruction generation      |
| UltraChat                 | 404K | English           | Conversational AI           |
| IGN Clean Instruct        | 509K | English           | Instruction tuning          |
| ELI5                      | 559K | English           | Long-form QA                |
| GPT4All                   | 806K | Multilingual      | General instruction         |
| Instruct                  | 889K | English           | Instruction tuning          |

---

# 🔥 Million-Scale Datasets

| Dataset            |  Size | Language     | Primary Use                          |
| ------------------ | ----: | ------------ | ------------------------------------ |
| MOSS               |    1M | Chinese      | SFT                                  |
| WildChat           |    1M | English      | Real-world conversation              |
| smolTalk           |  1.1M | English      | Compact conversational SFT           |
| Open-PerfectBlend  | 1.42M | English      | General SFT                          |
| The Tome           | 1.75M | English      | Instruction tuning                   |
| NaturalReasoning   |  2.8M | English      | Advanced reasoning                   |
| LaMini-Instruction |    3M | English      | Instruction tuning                   |
| OpenOrca Full      |    3M | English      | Instruction tuning                   |
| WildChat Nontoxic  |  3.2M | English      | Safe conversation                    |
| Infinity-Instruct  |  8.9M | Multilingual | Large-scale instruction              |
| BELLE              |   10M | Chinese      | Instruction tuning                   |
| Firefly            |   16M | Chinese      | Multi-task NLP                       |
| OIG                |   43M | Multilingual | General instruction                  |
| xP3                |   79M | Multilingual | Large-scale multilingual instruction |

---

# 🌍 Language Coverage

ForgeLM-Datasets includes datasets covering:

```text
English
Chinese
Japanese
Portuguese
Multilingual
Code
Image + Text
```

Major multilingual resources include:

* OASST
* Guanaco
* InstructionTranslation
* M2Lingual
* Infinity-Instruct
* OIG
* xP3

The catalog ranges from English-only datasets to datasets covering dozens of languages.

---

# 🧩 Specialized Dataset Categories

## 🧠 Reasoning

Useful for improving mathematical, logical, and scientific reasoning:

* TheoremQA
* GSM-IC
* OpenR1-Math
* NaturalReasoning
* arXiv Math Instruction

---

## 💻 Coding

Useful for coding assistants and programming-focused models:

* CodeAlpaca
* CodeParrot
* Function-calling datasets
* Tool-use datasets

---

## 🔧 Function Calling

Useful for agentic systems that need to invoke APIs, tools, and functions:

* BFCL
* OpenAPI Function Invocations
* xLAM Function Calling
* ToolACE
* glaive-function-calling-v2

---

## 🛡️ Safety & Alignment

Useful for safety training and preference alignment:

* WildGuardMix
* PKU-SafeRLHF
* Anthropic HH-RLHF
* WildJailbreak
* ProsocialDialog
* HelpSteer2
* UltraFeedback

---

## 💬 Conversational AI

Useful for chatbot and assistant development:

* ChatAlpaca
* Vicuna
* OASST
* OpenOrca
* UltraChat
* WildChat
* Blended Skill Talk

---

## 👁️ Multimodal AI

Useful for vision-language systems:

* cc_sbu_align
* LLaVA Visual Instruct
* M2Lingual

---

# 🏗️ ForgeLM Dataset Pipeline

```text
                   ┌───────────────────────┐
                   │   DATASET DISCOVERY    │
                   └───────────┬───────────┘
                               │
                               ▼
                   ┌───────────────────────┐
                   │   DATASET SELECTION   │
                   └───────────┬───────────┘
                               │
                               ▼
                   ┌───────────────────────┐
                   │  DOWNLOAD / COLLECT   │
                   └───────────┬───────────┘
                               │
                               ▼
                   ┌───────────────────────┐
                   │       MERGE           │
                   └───────────┬───────────┘
                               │
                               ▼
                   ┌───────────────────────┐
                   │     PREPROCESS        │
                   └───────────┬───────────┘
                               │
                               ▼
                   ┌───────────────────────┐
                   │  QUALITY / VALIDATION │
                   └───────────┬───────────┘
                               │
                               ▼
                   ┌───────────────────────┐
                   │   HUGGING FACE HUB    │
                   └───────────┬───────────┘
                               │
                               ▼
                   ┌───────────────────────┐
                   │    MODEL TRAINING     │
                   └───────────────────────┘
```

---

# 🧪 Example Training Dataset Architecture

A high-quality general-purpose dataset can be constructed by combining several categories:

```text
ForgeLM Training Mixture
│
├── Instruction Following
│   ├── Alpaca
│   ├── Dolly
│   └── Self-Instruct
│
├── Conversation
│   ├── OASST
│   ├── UltraChat
│   └── WildChat
│
├── Reasoning
│   ├── NaturalReasoning
│   ├── OpenR1-Math
│   └── TheoremQA
│
├── Coding
│   ├── CodeAlpaca
│   └── CodeParrot
│
├── Tool Usage
│   ├── BFCL
│   ├── xLAM
│   └── ToolACE
│
├── Safety
│   ├── WildGuard
│   ├── SafeRLHF
│   └── WildJailbreak
│
└── Multilingual
    ├── OASST
    ├── xP3
    └── Infinity-Instruct
```

---

# ⚙️ Preprocessing Workflow

The repository provides a simple workflow for selecting and preprocessing datasets.

```bash
git clone https://github.com/upadrastaharshavardhan/ForgeLM-datasets

cd ForgeLM-datasets/mixed/dataset

python preprocess.py <dataset_name>
```

The source project specifically describes selecting a dataset and then using `preprocess.py` to prepare it for Hugging Face Hub upload.

---

# 📦 Unknown / Mixed-Size Datasets

Some datasets in the original catalog do not have a reliable size listed. They are intentionally retained rather than removed.

| Dataset                    | Language     | Description                            |
| -------------------------- | ------------ | -------------------------------------- |
| CodeParrot                 | Python       | Large-scale Python code corpus         |
| Alpaca-CoT                 | Multilingual | Instruction data with reasoning traces |
| Stack Exchange Paired      | English      | Preference modeling                    |
| LangChainDatasets          | English      | Chain / agent evaluation               |
| ParlAI                     | English      | Dialogue research                      |
| GPTeacher                  | English      | General instruction                    |
| Wizard-LM Chinese Evol     | Chinese      | Evolved instructions                   |
| MultiWOZ                   | English      | Multi-domain dialogue                  |
| ToolACE                    | English      | Multi-tool calling                     |
| UltraFeedback              | English      | Preference optimization                |
| glaive-function-calling-v2 | English      | Function calling                       |

---

# ⚠️ Dataset & License Considerations

**Dataset licenses vary significantly.**

The catalog contains datasets under licenses including:

* MIT
* Apache-2.0
* CC-BY
* CC-BY-4.0
* CC-BY-NC
* CC-BY-NC-SA
* ODC-BY
* GPL
* Research-only terms
* OpenAI terms
* Dataset-specific licenses

Some datasets may restrict:

* Commercial use
* Redistribution
* Derivative datasets
* Model training
* Publication
* Dataset hosting

### Always verify the original dataset license before using a dataset in a commercial or public model.

The license information in this repository is intended as a discovery aid and should not replace review of the original dataset's license terms.

---

# 🧠 Recommended Dataset Mixtures

## General LLM

```text
30% Instruction
20% Conversation
15% Reasoning
15% Knowledge / QA
10% Coding
10% Safety / Preference
```

## Coding Model

```text
40% Code
20% Instruction
15% Reasoning
15% Tool Calling
10% Conversation
```

## Agent Model

```text
25% Instruction
20% Function Calling
20% Tool Usage
15% Reasoning
10% Conversation
10% Safety
```

> These percentages are example engineering strategies, not dataset-specific recommendations from the source catalog.

---

# 🎯 Why ForgeLM-Datasets?

### 🔎 One Place to Discover

Find datasets from many major AI research categories in one catalog.

### 🧩 Modular

Pick only the datasets required for your model.

### 📈 Scalable

The catalog ranges from tiny datasets to resources containing tens of millions of examples.

### 🌍 Multilingual

Supports English, Chinese, Japanese, Portuguese, multilingual and code-oriented resources.

### 🤖 Agent Ready

Includes datasets focused on function calling, tool usage and executable agents.

### 🛡️ Safety Ready

Includes safety, preference and jailbreak-related datasets.

### 🧪 Research Friendly

Useful for experimenting with SFT, alignment, evaluation, reasoning and specialized model training.

---

# 🔬 Research Use Cases

ForgeLM-Datasets can serve as a foundation for experiments involving:

```text
                ForgeLM-Datasets
                       │
       ┌───────────────┼────────────────┐
       ▼               ▼                ▼
     SFT            RLHF / DPO        Agents
       │               │                │
       ▼               ▼                ▼
 Instruction        Preference       Tool Use
   Tuning           Learning       Function Calls
       │               │                │
       └───────────────┼────────────────┘
                       ▼
                 Specialized LLM
                       │
       ┌───────────────┼────────────────┐
       ▼               ▼                ▼
   Coding          Reasoning        Multilingual
       │               │                │
       └───────────────┼────────────────┘
                       ▼
                  Production AI
```

---

# 📚 Dataset Sources

The catalog references datasets hosted across platforms and research repositories, including:

* Hugging Face Datasets
* GitHub research repositories
* Academic research projects
* Open-source AI organizations
* Research labs

Each dataset entry retains its original source information wherever available.

---

# 🤝 Contributing

Contributions are welcome.

You can contribute by:

1. Adding a useful open dataset.
2. Updating dataset metadata.
3. Correcting dataset links.
4. Adding language information.
5. Adding dataset categories.
6. Improving preprocessing utilities.
7. Adding validation or deduplication workflows.
8. Improving documentation.

### Suggested Dataset Entry

```text
Dataset Name:
Dataset Size:
Languages:
Source:
License:
Primary Use:
Hugging Face Link:
GitHub Link:
Notes:
```

---

# ⭐ Project Philosophy

ForgeLM-Datasets follows a simple philosophy:

> **Don't start dataset discovery from zero. Start from a curated foundation and build your own training mixture.**

The project is intended to reduce the friction between:

```text
Research
   ↓
Dataset Discovery
   ↓
Dataset Selection
   ↓
Data Engineering
   ↓
Model Training
   ↓
Evaluation
   ↓
Deployment
```

---

# 🚀 ForgeLM Ecosystem

ForgeLM-Datasets can act as the **data layer** for the broader ForgeLM ecosystem.

```text
                    ┌────────────────────┐
                    │   ForgeLM-Datasets │
                    │     DATA LAYER     │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Data Engineering   │
                    │ Preprocessing      │
                    │ Deduplication      │
                    │ Filtering          │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │    Model Training │
                    │     SFT / RLHF     │
                    │     DPO / LoRA     │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │     Evaluation     │
                    │ Reasoning / Safety │
                    │ Code / Agents      │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │    ForgeLM Model   │
                    └────────────────────┘
```

---

# 📊 Dataset Scale at a Glance

```text
1K
 │
 ├── Small Research Datasets
 │
10K
 │
 ├── Instruction / Safety
 │
100K
 │
 ├── Conversation / Alignment
 │
1M
 │
 ├── Large SFT Collections
 │
10M
 │
 ├── Large Instruction Corpora
 │
100M+
 │
 └── Massive Multilingual / Code Resources
```

The catalog currently spans resources from approximately **1K examples to tens of millions of examples**, with some datasets represented by storage/file size rather than example count.

---

# 🏁 Getting Started

```bash
# Clone
git clone https://github.com/upadrastaharshavardhan/ForgeLM-datasets

# Enter dataset workspace
cd ForgeLM-datasets/mixed/dataset

# Select your dataset
# Then preprocess
python preprocess.py <dataset_name>
```

From there, the resulting dataset can become part of your own LLM training pipeline.

---

# 👨‍💻 Developed By

<p align="center">

### Harsha Vardhan Upadrasta

**AI / ML Engineer • Automation Engineer • LLM & Agentic AI Researcher**

</p>

---

# ⭐ Support the Project

If ForgeLM-Datasets helps your research or development:

* ⭐ Star the repository
* 🍴 Fork the project
* 🧪 Experiment with different dataset mixtures
* 🛠️ Contribute new datasets
* 📢 Share it with other AI researchers

---

<p align="center">

### 🧬 ForgeLM-Datasets

**Discover datasets. Forge training mixtures. Build better models.**

</p>
