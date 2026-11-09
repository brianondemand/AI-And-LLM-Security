# AI Mastery Program: Full Lesson Syllabus (001 to 068)

*Your map for the whole course: from absolute beginner to AI engineer and AI security / penetration tester.*

**How to read this:**

- **Core** = AI/ML fundamentals and engineering. **Security** = the AI security and penetration-testing specialization, interleaved so that you attack and defend each thing right after you learn to build it.
- **Status:** Done, or Next, or blank (not started).
- This is a **plan, not a contract.** If a topic needs more depth I will split a lesson; if you want to skip something, tell me. Titles and order may shift slightly, but the destination stays the same.
- Every lesson uses the same 12-part structure (introduction, fundamentals, technical explanation, terminology, examples, practical demo, applications, security perspective, mistakes, takeaways, exercises, assessment). Labs are built into the lessons.
- All offensive exercises use intentionally vulnerable local labs, systems you own, or explicitly authorized targets.

## At a glance

| Stage | Lessons | Core | Security | What you can do at the end |
| --- | --- | --- | --- | --- |
| **Stage 1: Beginner** | 001 to 015 | 14 | 1 | Understand how machines learn; train and evaluate models; threat-model an ML pipeline |
| **Stage 2: Intermediate** | 016 to 036 | 15 | 6 | Build with deep learning, transformers, LLMs, RAG, and agents; attack and secure your own LLM apps |
| **Stage 3: Advanced** | 037 to 058 | 16 | 6 | Understand LLM internals, fine-tune, optimize, deploy; master adversarial ML and agent security |
| **Specialization: AI Pentesting** | 059 to 068 | 0 | 10 | Run professional AI security assessments, red-team, report, and retest |
| **Total** | **68** | **45** | **23** |  |

At about 4 to 6 hours per lesson that is roughly 270 to 410 hours in total.

---

# STAGE 1: BEGINNER (Lessons 001 to 015)

| No. | Lesson | Key topics | Type | Status |
| --- | --- | --- | --- | --- |
| 001 | Introduction to AI | What AI is; history; narrow vs general AI; AI vs ML vs DL | Core | Done |
| 002 | How Computers Learn and Make Decisions | Learning loop; loss; gradient descent; supervised, unsupervised, reinforcement; decision thresholds | Core | Done |
| 003 | Python for AI | Core Python, NumPy, Pandas, Matplotlib; Python supply-chain risks | Core | Done |
| 004 | Linear Algebra for AI (Part 1) | Vectors, dot product, norms, cosine similarity, matrices, layers; perturbation and model-extraction labs | Core | Done |
| 005 | Probability and Statistics for AI | Bayes' rule, base rates, distributions, softmax, cross-entropy, confidence intervals; membership-inference lab | Core | Done |
| 006 | Calculus for AI | Derivatives, partial derivatives, gradient, chain rule; derive the gradients from Lessons 002 and 003; gradients with respect to inputs | Core | **Next** |
| 007 | Data Science and Preprocessing | Datasets, cleaning, missing values, scaling, encoding, feature engineering, train/validation/test splits, data leakage | Core |  |
| 008 | Supervised Learning I: Regression | Linear and polynomial regression, regularization, overfitting and underfitting, bias and variance | Core |  |
| 009 | Supervised Learning II: Classification | Logistic regression, decision boundaries, probabilities and thresholds, multi-class | Core |  |
| 010 | Unsupervised Learning and PCA | Clustering (k-means), anomaly detection, dimensionality reduction; the extra linear algebra needed (inverses, eigenvectors, SVD intuition) | Core |  |
| 011 | Reinforcement Learning Basics | Agents, rewards, policies, Q-learning in a toy environment; reward hacking | Core |  |
| 012 | Training, Testing, and Evaluating Models | Confusion matrix, precision, recall, F1, ROC, cross-validation, imbalanced data, honest evaluation | Core |  |
| 013 | Introduction to Neural Networks | Neurons, weights, biases, activations, layers, forward pass, hyperparameters | Core |  |
| 014 | Lab: First Real Models | Train a model on a real dataset; build a small neural network from scratch with NumPy | Core (lab) |  |
| 015 | AI Threat Modeling and ML Pipeline Security | How AI systems are attacked; attack surfaces across data, training, model, and serving; threat-modeling an ML pipeline; toy poisoning and evasion labs | Security (Track A) |  |

**Milestone after 015:** you can explain how learning works mathematically, build and honestly evaluate classic ML models, and describe where in an ML pipeline attackers can strike.

---

# STAGE 2: INTERMEDIATE (Lessons 016 to 036)

| No. | Lesson | Key topics | Type | Status |
| --- | --- | --- | --- | --- |
| 016 | ML Algorithms in Depth I | Decision trees, random forests, feature importance | Core |  |
| 017 | ML Algorithms in Depth II | k-nearest neighbors, support vector machines, gradient boosting, choosing an algorithm | Core |  |
| 018 | Neural Networks and Backpropagation | The chain rule in action; backpropagation by hand and from scratch; vanishing gradients | Core |  |
| 019 | PyTorch Fundamentals | Tensors, autograd, building and training models; a first look at TensorFlow | Core |  |
| 020 | Training Deep Networks Well | Optimizers (SGD, Adam), learning-rate schedules, regularization, dropout, normalization, debugging training | Core |  |
| 021 | Convolutional Neural Networks | Convolutions, pooling, image classification with PyTorch | Core |  |
| 022 | Adversarial Examples and Evasion Attacks | Gradient-based evasion (FGSM, PGD), transferability, norm-bounded perturbations; attack a CNN you trained | Security (Track B) |  |
| 023 | Recurrent Networks and LSTMs | Sequences, RNNs, LSTMs, the limits that led to transformers | Core |  |
| 024 | NLP, Tokenization, and Embeddings | Text preprocessing, tokenizers (BPE), word and sentence embeddings, similarity search | Core |  |
| 025 | Attention and Transformers | Self-attention, multi-head attention, positional encoding, the transformer block | Core |  |
| 026 | Large Language Models | GPT-style architecture, next-token prediction, sampling, how LLMs are trained and fine-tuned (overview) | Core |  |
| 027 | Local Models, Hugging Face, and Evaluation | Ollama, Hugging Face Hub, quantization basics, inference, benchmarking and evaluating LLMs | Core |  |
| 028 | LLM Security Frameworks and the Vulnerable Lab App | OWASP Top 10 for LLM Applications, MITRE ATLAS, NIST AI RMF; build an intentionally vulnerable local LLM app | Security (Track A) |  |
| 029 | Prompt Injection | Direct and indirect prompt injection against your lab app; why it is hard to fix; first defenses | Security (Track C) |  |
| 030 | Jailbreaks, System Prompt Leakage, and Data Disclosure | Jailbreak techniques and why they work, system prompt extraction, sensitive information disclosure; testing and mitigation | Security (Track C) |  |
| 031 | Vector Databases and RAG | Embeddings at scale, chunking, retrieval, building a RAG application | Core (lab) |  |
| 032 | RAG, Vector DB, and Output-Handling Attacks | RAG poisoning, vector database attacks, insecure output handling (XSS and injection through LLM output); fixes | Security (Track C) |  |
| 033 | AI Agents and Agentic AI | Tool calling, planning loops, memory, building a simple agent | Core (lab) |  |
| 034 | Agent Security I | Excessive agency, insecure tool integration, privilege escalation, exploiting a vulnerable agent in your lab | Security (Track D) |  |
| 035 | Generative AI: Images, Audio, Video | Autoencoders, GANs, diffusion models, speech and audio models; misuse risks | Core |  |
| 036 | Stage 2 Capstone: Build and Break an LLM App | Build a small LLM-powered application, then threat-model, attack, and harden it | Capstone |  |

**Milestone after 036:** you can build real LLM applications (chat, RAG, agents), run models locally, and find and fix the most common LLM vulnerabilities in your own projects.

---

# STAGE 3: ADVANCED (Lessons 037 to 058)

| No. | Lesson | Key topics | Type | Status |
| --- | --- | --- | --- | --- |
| 037 | Advanced Deep Learning Architectures | Residual networks, normalization variants, autoencoders and VAEs, graph and other modern architectures | Core |  |
| 038 | Advanced Transformer Architectures | Encoder vs decoder vs encoder-decoder, positional encoding variants, efficient attention, mixture of experts | Core |  |
| 039 | LLM Internals | Inside a transformer block: attention heads, KV cache, residual stream, how a prompt becomes a response | Core |  |
| 040 | Lab: Build a Mini GPT from Scratch | Implement and train a tiny GPT-style model in PyTorch | Core (lab) |  |
| 041 | Pretraining, Data, and Scaling | Pretraining data pipelines, tokenization at scale, scaling laws, training costs | Core |  |
| 042 | Data Poisoning, Model Poisoning, and Backdoors | Poisoning attacks, trojans and triggers, detection and defenses; hands-on backdoor lab on a small model | Security (Track B) |  |
| 043 | Fine-tuning, RLHF, and Preference Optimization | Supervised fine-tuning, reward models, RLHF, DPO and related methods | Core |  |
| 044 | Parameter-Efficient Fine-tuning: LoRA and QLoRA | Fine-tune a small open-source model on your own data | Core (lab) |  |
| 045 | Model Extraction, Inversion, and Membership Inference | Stealing models via queries, recovering training data, privacy attacks, defenses including differential privacy | Security (Track B) |  |
| 046 | GPU Computing and CUDA Fundamentals | How GPUs work, memory, kernels, profiling PyTorch workloads | Core |  |
| 047 | Distributed Training and Inference | Data/tensor/pipeline parallelism, serving large models | Core |  |
| 048 | Model Compression and Quantization | Pruning, distillation, 8-bit and 4-bit quantization, accuracy tradeoffs | Core |  |
| 049 | AI Supply Chain Security | Model hubs, unsafe serialization (pickle), safetensors, dependency and dataset risks, model provenance | Security (Track A) |  |
| 050 | Multimodal AI Systems | Vision-language models, audio, cross-modal embeddings; multimodal attack surface | Core |  |
| 051 | Advanced Agents and Autonomous Workflows | Multi-step planning, memory, multi-agent systems, workflow orchestration | Core |  |
| 052 | Agent Security II | Memory poisoning, multi-agent risks, insecure integrations, securing autonomous workflows | Security (Track D) |  |
| 053 | Interpretability and Explainable AI | Feature attribution, probing, attention analysis, circuits at an introductory level; limits of explanations | Core |  |
| 054 | Adversarial Robustness and Defenses | Adversarial training, input preprocessing, detection, certified robustness, evaluating defenses properly | Security (Track B) |  |
| 055 | AI Alignment, Safety, and Responsible AI | Alignment problem, safety evaluations, bias and fairness, governance and regulation overview | Core |  |
| 056 | AI Research Methodology | Reading papers, reproducing results, experiment design, statistics for evaluation, writing up findings | Core |  |
| 057 | Building and Deploying Production AI Applications | Serving, APIs, monitoring, evaluation in production, MLOps basics, cost and latency | Core |  |
| 058 | Securing Deployed AI Systems | LLM denial of service, model theft and API abuse, insecure architectures, rate limiting, guardrails, monitoring and incident response | Security (Track C) |  |

**Milestone after 058:** you understand modern models from the math up, can fine-tune and deploy them, and know the full catalog of adversarial ML, LLM, and agent attacks and defenses.

---

# SPECIALIZATION: AI PENETRATION TESTING AND RED TEAMING (Lessons 059 to 068)

| No. | Lesson | Key topics | Type | Status |
| --- | --- | --- | --- | --- |
| 059 | AI Pentest Methodology and Lab Setup | Scoping and rules of engagement, test plans, Burp Suite for AI application testing, building a test lab | Security (Track E) |  |
| 060 | Garak | LLM vulnerability scanning: installation, configuration, probes, detectors, interpreting results | Security (Track E) |  |
| 061 | PyRIT | Microsoft's red-teaming framework: targets, orchestrators, scoring, automated attack campaigns | Security (Track E) |  |
| 062 | Promptfoo and Giskard | Test suites and regression testing for LLM apps, red-team configuration, vulnerability scans | Security (Track E) |  |
| 063 | ART, Foolbox, and TextAttack | Adversarial robustness toolkits for images, tabular, and text models; running and comparing attacks | Security (Track E) |  |
| 064 | Custom Python Tooling for AI Security Testing | Writing your own harnesses, fuzzers, attack scripts, result logging, reproducible test cases | Security (Track E) |  |
| 065 | Full AI Red-Team Engagement (Lab) | End-to-end assessment of a multi-component AI system: recon, attack, exploitation, evidence | Security (Track F) |  |
| 066 | Mitigation and Defense Engineering | Guardrails, filters, least privilege, secure architectures, monitoring; implementing and testing fixes | Security (Track F) |  |
| 067 | Reporting and Retesting | Writing professional AI pentest reports, severity rating, remediation advice, retest methodology | Security (Track F) |  |
| 068 | Final Capstone: Assess and Secure a Complete AI Application | Build, assess, report, remediate, and retest an AI application from start to finish | Capstone |  |

**Final milestone after 068:** you can build AI systems and professionally assess their security: running authorized AI penetration tests, red-teaming, writing reports, and implementing and verifying mitigations.

---

## Key dependencies (why the order is what it is)

- **Calculus (006)** comes before backpropagation (018), because backprop is the chain rule applied repeatedly.
- **Probability (005)** comes before evaluation (012) and generative models (035).
- **CNNs (021)** come before adversarial examples (022), because evasion attacks need a trained model and gradients.
- **LLMs and local models (026 and 027)** come before any LLM security lesson (028 to 030).
- **RAG (031)** comes before RAG attacks (032); **agents (033)** come before agent security (034).
- **LLM internals (039 to 041)** come before poisoning and backdoors (042) and fine-tuning (043 and 044).
- **All building lessons come before the tooling lessons (059 to 064)**, so that when you run Garak, PyRIT, and the rest, you understand exactly what each test is probing.

## Tools and frameworks, and where you meet them

| Tool or framework | First lesson |
| --- | --- |
| NumPy, Pandas, Matplotlib | 003 |
| scikit-learn | 001, then 008 to 012 and 016 and 017 |
| PyTorch | 019 (TensorFlow overview also there) |
| Hugging Face, Ollama | 027 |
| OWASP Top 10 for LLM Applications, MITRE ATLAS, NIST AI RMF | Mentioned from 001; studied in 028 |
| Burp Suite, Garak, PyRIT, Promptfoo, Giskard, ART, Foolbox, TextAttack | 059 to 063 (plus earlier previews in 022 and 029) |

## Pace suggestion

At 8 to 10 hours a week (about two lessons per week with exercises) the full course is roughly 8 to 9 months. At 4 to 5 hours per week expect closer to 16 to 18 months. Quality matters more than speed: do the hand calculations and exercises, send me your answers, and I will adapt the pace.

## Progress

**Completed:** 001, 002, 003, 004, 005. **Up next:** 006, Calculus for AI. Say "Lesson 6" whenever you are ready.
