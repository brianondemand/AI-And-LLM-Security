# AI & LLM Security

> A hands-on journey into Artificial Intelligence, Machine Learning, Deep Learning, and Large Language Models — from beginner fundamentals to advanced AI engineering, security research, and ethical AI red teaming.

**Maintained by [Zeroday Academy](https://github.com/zerodayacademy)**

[![Learning](https://img.shields.io/badge/Status-Actively%20Learning-76B900?style=flat-square)](#learning-roadmap)
[![Python](https://img.shields.io/badge/Language-Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Focus](https://img.shields.io/badge/Focus-AI%20%26%20Cybersecurity-FF5F1F?style=flat-square)](#ai-security--red-teaming)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

## About This Repository

This repository documents my structured learning journey in Artificial Intelligence and AI cybersecurity. It is designed to grow from beginner-friendly study notes into a practical technical knowledge base containing explanations, code examples, experiments, projects, and security labs.

My goal is to understand how AI systems work internally, learn how to build and evaluate them, and develop the skills to assess and secure them.

I already have a background in cybersecurity and ethical hacking. This repository builds on that foundation and applies it to the emerging field of AI security.

## Learning Objectives

By working through this repository, I aim to learn how to:

- Explain the foundations of AI, machine learning, and deep learning.
- Understand the mathematics and programming behind AI.
- Train, evaluate, and improve machine learning models.
- Understand neural networks, transformers, and LLMs.
- Build AI applications using Python and open-source tools.
- Run, configure, and experiment with local AI models.
- Build applications using embeddings, vector databases, and RAG.
- Understand AI agents and their security implications.
- Identify and assess vulnerabilities in AI-powered applications.
- Perform authorized AI penetration testing and red-team exercises.
- Apply security controls and document assessment findings.

## Learning Roadmap

The roadmap is divided into three learning stages, followed by a dedicated AI security specialization. Topics will be studied progressively, with practical exercises and projects wherever possible.

### Stage 1 — Beginner: AI Fundamentals

Build a strong foundation before moving into advanced concepts.

| Module | Topics |
|---|---|
| AI Fundamentals | What AI is, its history, types of AI, and real-world applications |
| Python for AI | Python fundamentals, functions, data structures, libraries, and notebooks |
| Mathematics for AI | Linear algebra, probability, statistics, and introductory calculus |
| Data Science | Datasets, data collection, cleaning, preprocessing, and visualization |
| Machine Learning | Supervised, unsupervised, and reinforcement learning |
| Model Evaluation | Training, validation, testing, metrics, overfitting, and underfitting |
| Neural Network Basics | Neurons, layers, weights, biases, activation functions, and loss |

### Stage 2 — Intermediate: Modern AI and Model Development

Learn how modern AI systems are designed, trained, and used.

| Module | Topics |
|---|---|
| Machine Learning Algorithms | Regression, classification, clustering, and model selection |
| Deep Learning | Neural networks, backpropagation, CNNs, RNNs, and LSTMs |
| Transformers | Attention mechanisms, encoder/decoder architectures, and tokenization |
| Natural Language Processing | Text processing, language models, and embeddings |
| Large Language Models | LLM architecture, inference, training concepts, and limitations |
| Generative AI | Text, image, audio, and video generation |
| RAG | Retrieval-Augmented Generation, vector databases, and retrieval pipelines |
| AI Agents | Tool calling, workflows, memory, and agent architectures |
| Model Tooling | PyTorch, TensorFlow, Hugging Face, and local model runtimes |

### Stage 3 — Advanced: AI Engineering and Research

Develop the ability to build, optimize, evaluate, and deploy AI systems.

- Advanced neural network and transformer architectures.
- Pretraining, supervised fine-tuning, and preference optimization.
- Reinforcement Learning from Human Feedback (RLHF).
- Parameter-efficient fine-tuning, including LoRA and QLoRA.
- Quantization, pruning, and model optimization.
- GPU computing and distributed training fundamentals.
- Multimodal models and systems.
- Advanced RAG and agentic workflows.
- Model interpretability and evaluation.
- AI safety, alignment, and responsible AI.
- Production deployment, monitoring, and performance evaluation.

### Stage 4 — AI Security and Red Teaming

Apply cybersecurity knowledge to AI systems and learn how to test them responsibly.

#### AI Security Fundamentals

- AI threat modeling and attack surfaces.
- Machine learning security concepts.
- OWASP Top 10 for LLM Applications.
- MITRE ATLAS.
- NIST AI Risk Management Framework.
- AI supply-chain and data-pipeline security.

#### Adversarial Machine Learning

- Adversarial examples and evasion attacks.
- Data poisoning and model poisoning.
- Model extraction and model inversion.
- Membership inference.
- Backdoor and trojan attacks.
- Adversarial robustness and defensive techniques.

#### LLM and AI Application Security

- Direct and indirect prompt injection.
- Jailbreaks and instruction-conflict testing.
- Sensitive information disclosure.
- Insecure output handling.
- Insecure tool integration and excessive agency.
- RAG and vector database security.
- AI application authentication and authorization.
- Denial-of-service and resource-exhaustion risks.
- AI agent memory and tool-permission risks.

#### AI Penetration Testing and Red Teaming

- AI application reconnaissance and threat modeling.
- Mapping trust boundaries and data flows.
- Designing repeatable security test cases.
- Testing prompts, retrieval pipelines, tools, and agent workflows.
- Assessing model and application robustness.
- Validating mitigations and retesting.
- Writing professional AI security assessment reports.

## Tools and Technologies

The tools below are part of the planned learning environment. They will be introduced when relevant; not every tool is required for every module.

| Area | Tools and technologies |
|---|---|
| Programming | Python, Jupyter Notebook |
| Data and ML | NumPy, pandas, scikit-learn |
| Deep Learning | PyTorch, TensorFlow |
| Model Ecosystem | Hugging Face |
| Local AI | Ollama and compatible open-source models |
| Generative AI | ComfyUI and selected open-source models |
| RAG and Data | Embedding models, vector databases |
| AI Security | Garak, PyRIT, Promptfoo, Giskard |
| Adversarial ML | Adversarial Robustness Toolbox (ART), Foolbox, TextAttack |
| Security Testing | Kali Linux, Burp Suite, Python |

Tool selection may change as projects and documentation evolve.

## Repository Structure

The repository is organized so that notes, code, labs, and projects remain easy to find.

```text
ai-and-llm-security/
├── 01-ai-fundamentals/
├── 02-python-for-ai/
├── 03-mathematics-for-ai/
├── 04-machine-learning/
├── 05-deep-learning/
├── 06-neural-networks/
├── 07-transformers-and-llms/
├── 08-generative-ai/
├── 09-ai-agents/
├── 10-ai-engineering/
├── 11-ai-security-fundamentals/
├── 12-adversarial-machine-learning/
├── 13-llm-security/
├── 14-prompt-injection/
├── 15-ai-penetration-testing/
├── 16-ai-red-teaming/
├── 17-ai-security-labs/
├── projects/
├── resources/
└── README.md
```

Individual modules may contain:

```text
module-name/
├── README.md          # Module overview
├── notes/             # Detailed study notes
├── examples/          # Code and demonstrations
├── exercises/         # Practice questions and tasks
└── resources.md       # Documentation and further reading
```

## How Each Topic Is Documented

To make the repository useful as a long-term reference, lessons aim to follow a consistent structure:

1. **Introduction** — What the concept is and why it matters.
2. **Core concepts** — Important principles and terminology.
3. **Technical explanation** — How it works internally.
4. **Examples** — Simple examples followed by more realistic ones.
5. **Practical work** — Code, commands, experiments, or lab exercises.
6. **Real-world applications** — Where and why the concept is used.
7. **Security perspective** — Relevant risks, attack scenarios, and defenses.
8. **Common mistakes** — Misconceptions and troubleshooting.
9. **Key takeaways** — Main points to remember.
10. **Exercises** — Questions and practical challenges.
11. **References** — Official documentation, research papers, and further reading.

## Practical Projects

Projects will be added as the relevant foundations are covered. Planned ideas include:

- Train and evaluate a machine learning model.
- Build a neural network and inspect its behavior.
- Create a simple chatbot.
- Run and compare local LLMs.
- Build a basic RAG application.
- Fine-tune a small open-source model.
- Create an AI agent with controlled tool access.
- Build an intentionally vulnerable LLM application.
- Test a local AI application for prompt injection.
- Evaluate a model using adversarial examples.
- Conduct an AI red-team assessment and document findings.
- Implement and validate security mitigations.

## Responsible Security Research

All offensive security exercises in this repository are intended for authorized learning and research.

- Test only systems you own or have explicit permission to assess.
- Use intentionally vulnerable applications and isolated local labs for exploitation exercises.
- Do not use these techniques to access, disrupt, manipulate, or extract data from systems without authorization.
- Protect private data, API keys, credentials, and model secrets.
- Document findings clearly and recommend practical mitigations.
- Follow applicable laws, responsible disclosure practices, and platform rules.

The purpose is to understand AI weaknesses so that AI systems can be tested and made more secure.

## Learning Progress

This repository is a work in progress. Progress will be updated as modules, exercises, and projects are completed.

- [ ] Stage 1 — AI Fundamentals
- [ ] Stage 2 — Modern AI and Model Development
- [ ] Stage 3 — Advanced AI Engineering
- [ ] Stage 4 — AI Security and Red Teaming
- [ ] Build a collection of practical AI projects
- [ ] Complete an end-to-end AI security assessment in a local lab

## Learning Resources

The following official resources are useful starting points. More references will be added to the relevant modules.

- [Python Documentation](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [TensorFlow Documentation](https://www.tensorflow.org/learn)
- [Hugging Face Documentation](https://huggingface.co/docs)
- [OWASP Top 10 for LLM Applications](https://genai.owasp.org/)
- [MITRE ATLAS](https://atlas.mitre.org/)
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [Adversarial Robustness Toolbox](https://adversarial-robustness-toolbox.readthedocs.io/)

## Why This Repository?

AI is changing how software is developed, how organizations operate, and how security is approached. Understanding how these systems work — and how they can fail — is becoming an important technical skill.

This repository is my effort to build that understanding through structured study, experimentation, open-source tools, and practical security research.

**Learn AI. Build AI. Break AI ethically. Secure AI.**

---

**Part of the Zeroday Academy learning journey.**

If you find the notes useful, feel free to explore, learn, and share feedback.
