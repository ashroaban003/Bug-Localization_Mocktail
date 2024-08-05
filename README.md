# 🐞 Bug Localizer Tool

**Bug Localizer** is a tool designed to help software developers to find buggy files based on the bug reported in Java source code repositories using deep learning techniques. This tool processes bug reports and extracts features from Abstract Syntax Trees (ASTs) and Control Flow Graphs (CFGs) to train a model that accurately predicts bug files.

## ✨ Features

- **Data Collection**: Collects and preprocesses bug reports and Java source code files.
- **Source Code Analysis**: Constructs ASTs, CFGs, and Program Dependence Graphs (PDGs).
- **Feature Extraction**: Utilizes advanced techniques like BERT embeddings.
- **Model Training**: Trains a transformer model to predict potential bug locations.
- **Bug Localization**: Identifies probable files where bugs are likely to occur.

## 🛠️ Tools Used

- **Python**: For developing the tool and preprocessing data.
- **Java**: For analyzing the source code.
- **Pandas**: For reading and preprocessing CSV files.
- **SrcML**: For extracting ASTs.
- **Progex**: For extracting CFGs.
- **Comex**: For extracting PDGs and combining representations of source codes.

## ⚠️ Limitations

- Limited dataset diversity and system configuration constraints.
- Dependency on bug report quality.
- Currently supports only Java source code.

## 🚀 Future Work

- Expanding to support other programming languages.
- Enhancing model training with more diverse datasets.
- Integrating with popular IDEs for real-time bug localization.
- Encouraging community contributions for continuous improvement.

## 👥 Contributors

- **Rajeev Thota** - [GitHub](https://github.com/rajeevthota)
- **Nithin Chepuri** - [GitHub](https://github.com/NithinChepuri)
- **Sai Vignesh** - [GitHub](https://github.com/SaiVignesh-K)
- **Sreya Tejeswi** - [GitHub](https://github.com/rajeevthota) 
- **Ashish Kumar** - [GitHub](https://github.com/rajeevthota) 

## 📚 References

- [Transformers](https://arxiv.org/abs/1706.03762)
- [Bug Localization](https://ieeexplore.ieee.org/document/4318097)
