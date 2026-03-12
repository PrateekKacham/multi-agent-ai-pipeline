# 🤖 Multi-Agent AI Pipeline

**CSYE 7380 – Generative AI & Deep Models | Northeastern University**  
A collection of 8 assignments spanning multi-agent systems, deep learning, LLM fine-tuning, and generative models — built for production-quality AI/ML engineering.

---

## 📁 Repository Structure

```
multi-agent-ai-pipeline/
├── notebooks/
│   ├── kafka_pubsub.ipynb
│   ├── cnn_cifar10.ipynb
│   ├── nl2sql.ipynb
│   ├── cifar10_multiagent_classifier.ipynb
│   ├── dcgan_cifar10.ipynb
│   └── early/
│       ├── autogen_teacher_student.ipynb
│       ├── llm_prompting_neural_network.ipynb
│       └── neural_network_insurance.ipynb
├── requirements.txt
└── README.md
```

---

## 🧠 Assignments Overview

### Core Notebooks (`notebooks/`)

| Notebook | Topic | Score |
|----------|-------|-------|
| `kafka_pubsub.ipynb` | Kafka pub/sub pipeline with 3 coordinating agents | 100/100 |
| `cnn_cifar10.ipynb` | CNN on CIFAR-10 with BatchNorm, Dropout, activation experiments | 100/100 |
| `nl2sql.ipynb` | Natural language to SQL using LLM prompt engineering | 100/100 |
| `cifar10_multiagent_classifier.ipynb` | CNN + ResNet agents with an AutoGen Judge agent | 95/100 |
| `dcgan_cifar10.ipynb` | DCGAN with fully convolutional architecture on CIFAR-10 | 100/100 |

### Early Assignments (`notebooks/early/`)

| Notebook | Topic | Score |
|----------|-------|-------|
| `autogen_teacher_student.ipynb` | AutoGen Teacher–Student multi-agent conversation | 100/100 |
| `llm_prompting_neural_network.ipynb` | Few-shot & CoT prompting + MLP loan approval classifier | 93/100 |
| `neural_network_insurance.ipynb` | Prudential insurance risk prediction; ordinal regression (best κ = 0.5675) | 100/100 |



---

## 🔬 Technical Highlights

### Multi-Agent Systems
- **Microsoft AutoGen** framework for orchestrating CNN-CIFAR, ResNet-CIFAR, and Judge agents
- **Apache Kafka** pub/sub pipeline with producer/consumer agents for real-time data flow
- Teacher–Student agent pair with turn-based message passing

### Deep Learning
- Custom CNN on CIFAR-10 with **BatchNorm**, **Dropout**, and activation function experiments (ReLU, LeakyReLU, ELU)
- **ResNet-18** transfer learning for comparative classification benchmarking
- **DCGAN** with fully convolutional generator/discriminator replacing all Dense layers — trained on CIFAR-10

### LLM & NLP
- **NL-to-SQL** translation via structured LLM prompt engineering — zero-shot and few-shot approaches
- **Mistral 7B** fine-tuned with **QLoRA** (4-bit quantization) on a text-to-SQL dataset using Google Colab A100
- Few-shot and **Chain-of-Thought prompting** for loan approval classification

### Classical ML
- Ordinal regression for Prudential Life Insurance risk prediction
- Optimized for **Cohen's Kappa** (best κ = 0.5675) on an imbalanced multi-class target

---

## 🚀 Getting Started

```bash
git clone https://github.com/<your-username>/multi-agent-ai-pipeline.git
cd multi-agent-ai-pipeline
pip install -r requirements.txt
jupyter notebook
```

> GPU recommended for DCGAN, CIFAR-10 CNN, and fine-tuning notebooks. Google Colab (A100) was used for the Mistral QLoRA assignment.

---

## 🛠️ Tech Stack

`Python` · `PyTorch` · `Microsoft AutoGen` · `Apache Kafka` · `Hugging Face Transformers` · `PEFT / QLoRA` · `scikit-learn` · `Gradio` · `Google Colab`

---

## 👤 Author

**Sai Vinayaka Venkata Prateek Kacham**  
MS Information Systems, Northeastern University  
[LinkedIn](https://linkedin.com/in/prateek-kacham-32ba5a338) · [GitHub](https://github.com/PrateekKacham) · kacham.sai@northeastern.edu
