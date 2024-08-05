# 🐞 Bug Localizer

**Bug Localizer** is a tool designed to help software developers pinpoint and fix bugs in Java source code repositories using deep learning techniques. This tool processes bug reports and extracts features from Abstract Syntax Trees (ASTs) and Control Flow Graphs (CFGs) to train a model that accurately predicts bug locations.

## ✨ Features

- 📥 **Data Collection**: Collects and preprocesses bug reports and Java source code files.
- 📊 **Source Code Analysis**: Constructs ASTs, CFGs, and Program Dependence Graphs (PDGs).
- 🔍 **Feature Extraction**: Utilizes advanced techniques like BERT embeddings.
- 🧠 **Model Training**: Trains a transformer model to predict potential bug locations.
- 🗺️ **Bug Localization**: Identifies probable areas where bugs are likely to occur.

## 🛠️ Tools Used

- 🐍 **Python**: For developing the tool and preprocessing data.
- ☕ **Java**: For analyzing the source code.
- 📋 **Pandas**: For reading and preprocessing CSV files.
- 🌳 **SrcML**: For extracting ASTs.
- 🕸️ **Progex**: For extracting CFGs.
- 🧩 **Comex**: For extracting PDGs and combining representations.

## ⚠️ Limitations

- ⚙️ Limited dataset diversity and system configuration constraints.
- 📝 Dependency on bug report quality.
- ⛔ Currently supports only Java source code.

## 🚀 Future Work

- 🌐 Expanding to support other programming languages.
- 📈 Enhancing model training with more diverse datasets.
- 🛠️ Integrating with popular IDEs for real-time bug localization.
- 🤝 Encouraging community contributions for continuous improvement.

## 👥 Contributors

- **Rajeev Thota** - [GitHub](https://github.com/rajeevthota) - Project Lead
- **[Teammate 1]** - [GitHub](#) - [Role/Contribution]
- **[Teammate 2]** - [GitHub](#) - [Role/Contribution]
- **[Teammate 3]** - [GitHub](#) - [Role/Contribution]
- **[Teammate 4]** - [GitHub](#) - [Role/Contribution]

## 📚 References

- [Transformers](https://arxiv.org/abs/1706.03762)
- [Bug Localization](https://ieeexplore.ieee.org/document/4318097)
