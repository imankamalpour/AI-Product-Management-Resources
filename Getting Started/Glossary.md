# AI Product Management Glossary

Welcome to the AI Product Management Glossary.

Artificial Intelligence introduces hundreds of new concepts, acronyms, and technical terms that can feel overwhelming at first. This glossary provides concise, practical definitions of the most common terms you'll encounter throughout this repository and in your day-to-day work as an AI Product Manager.

> **Note**
>
> This glossary focuses on understanding concepts from a product perspective rather than explaining implementation details. Each definition is intentionally brief. For deeper explanations, refer to the relevant chapters in this repository.

---

# How to Use This Glossary

- Use **Ctrl + F** (or **Cmd + F**) to quickly find a term.
- New terms will be added regularly as the repository grows.
- Related concepts are referenced whenever possible.

---

# A

## Agent

An AI system capable of reasoning, planning, using tools, and taking actions to achieve a goal. Unlike traditional chatbots, agents can perform multi-step tasks with varying degrees of autonomy.

Related: AI Agent, Tool Calling, MCP, Memory

---

## AI Product Manager

A Product Manager responsible for discovering, designing, launching, and improving products that use Artificial Intelligence to solve customer problems.

Unlike traditional Product Managers, AI Product Managers also consider model capabilities, evaluation, prompt design, AI safety, and operational costs.

---

## API (Application Programming Interface)

A standardized way for different software systems to communicate with each other.

AI products frequently use APIs to access Large Language Models, vector databases, search engines, and third-party services.

---

## Alignment

🤖 AI Concepts

The degree to which an AI model behaves according to human intentions, values, and desired objectives rather than simply optimizing a mathematical training objective.

Alignment is one of the central challenges in modern AI because a capable model is not necessarily a trustworthy one.

---

## Annotation (Labeling)

📊 Data

The process of assigning labels or tags to raw data so it can be used for training or evaluating machine learning models.

Examples include labeling images with objects, categorizing emails as spam or not spam, or marking the correct answer in question-answer datasets.

High-quality annotation is essential for building reliable AI systems.

---

# B

## Bias

A systematic error in AI outputs caused by skewed training data, model behavior, or flawed evaluation methods.

Bias can lead to unfair, inaccurate, or discriminatory outcomes.

---

## Benchmark

A standardized test used to compare the performance of AI models.

Examples include MMLU, HumanEval, SWE-bench, and MMMU.

---

# C

## Chunking

The process of splitting large documents into smaller sections before creating embeddings for Retrieval-Augmented Generation (RAG).

Good chunking significantly improves retrieval quality.

---

## Context Window

The maximum amount of information an AI model can process in a single request.

A larger context window allows the model to consider more documents, conversations, or instructions simultaneously.

---

## Chain of Thought (CoT)

🧠 LLMs | 📝 Prompt Engineering

A prompting technique that encourages a language model to reason through intermediate steps before producing its final answer.

Chain of Thought often improves performance on tasks involving logic, mathematics, planning, and multi-step reasoning.

Note that modern reasoning models may perform internal reasoning automatically, so explicit Chain of Thought prompting is not always necessary.

---

## Confidence Score

📊 Evaluation

A numerical estimate representing how confident a model is in a particular prediction or response.

Product teams often use confidence scores to determine whether an answer should be shown directly, verified by a human, or rejected.

---

# D

## Deterministic System

A system that always produces the same output for the same input.

Traditional software is generally deterministic.

---

## Data Drift / Model Drift

📊 Evaluation

The gradual decline in AI performance caused by changes in real-world data or user behavior after deployment.

- **Data Drift** occurs when incoming data differs from the original training data.
- **Model Drift** refers to the resulting degradation in model performance.

Monitoring drift is a critical responsibility for AI product teams.

---

## Distillation

🧠 Model Optimization

A technique where a smaller AI model is trained to imitate the behavior of a larger model.

Distillation is commonly used to reduce inference cost, improve latency, and enable deployment on resource-constrained devices.

---

# E

## Embedding

A numerical representation of text, images, or other data that captures semantic meaning.

Embeddings enable semantic search, recommendations, clustering, and Retrieval-Augmented Generation.

---

## Evaluation

The process of measuring AI quality using predefined metrics.

Unlike traditional software testing, AI evaluation often includes qualitative and probabilistic measurements.

---

# F

## Fine-Tuning

The process of further training a pre-trained AI model on a specialized dataset to improve performance for a specific task.

Fine-tuning differs from prompt engineering because it changes the model itself.

---

## False Positive / False Negative

📊 Evaluation Metrics

Two fundamental concepts used to evaluate AI systems.

- **False Positive:** The model incorrectly predicts a positive result.
- **False Negative:** The model fails to identify a true positive.

The acceptable balance between false positives and false negatives depends on the product and business context.

---

## Few-Shot Learning

📝 Prompt Engineering

A prompting technique where a small number of examples are provided within the prompt to guide the model's behavior.

Few-shot prompting often improves consistency without requiring model retraining.

---

## Foundation Model

🧠 LLMs

A large, general-purpose AI model trained on diverse datasets that can be adapted for many downstream tasks through prompting or fine-tuning.

Examples include GPT-5, Claude, Gemini, Llama, and Mistral.

---

# G

## Generative AI

Artificial Intelligence capable of creating new content, including text, images, audio, video, and code.

Examples include ChatGPT, Claude, Gemini, and GitHub Copilot.

---

## Grounding

The practice of ensuring AI responses are based on trusted external knowledge rather than relying solely on the model's internal training.

Grounding is a key objective of Retrieval-Augmented Generation (RAG).

---

# H

## Hallucination

An incorrect or fabricated response generated confidently by an AI model.

Hallucinations are one of the primary risks AI Product Managers must monitor and mitigate.

---

## Human-in-the-Loop (HITL)

🏢 Enterprise AI | 🔐 AI Safety

A workflow in which human reviewers verify, approve, or correct AI-generated outputs before they are finalized or acted upon.

Human-in-the-Loop systems are commonly used in healthcare, finance, legal, and other high-risk domains where AI decisions require oversight.

---

# I

## Inference

The process of generating predictions or responses using a trained AI model.

Every interaction with ChatGPT, Claude, or another LLM is an inference.

---

# J

## JSON

A lightweight data format commonly used for exchanging structured information between software systems.

Modern AI applications often use structured JSON outputs to improve reliability.

---

# K

## Knowledge Base

A structured collection of documents and information that AI systems use as a trusted source during retrieval.

---

# L

## Large Language Model (LLM)

A neural network trained on massive amounts of text to understand and generate human language.

Examples include GPT-5, Claude, Gemini, Llama, and Mistral.

---

## Latency

The time between sending a request and receiving a response.

Reducing latency improves user experience but may increase infrastructure costs.

---

# M

## MCP (Model Context Protocol)

An open protocol that standardizes how AI applications communicate with external tools, resources, and prompts.

MCP simplifies integrations and enables more capable AI agents.

---

## Memory

Information retained across interactions that allows an AI system to maintain context over time.

Memory can be temporary (conversation history) or persistent (long-term user preferences).

---

## Model

An AI system trained to perform tasks such as generating text, classifying images, or answering questions.

---

# O

## Overfitting

🧠 Machine Learning

A situation where a model performs exceptionally well on its training data but poorly on new or unseen data because it has memorized patterns rather than learned to generalize.

Overfitting reduces a model's real-world effectiveness.

---

# P

## Prompt

The instruction provided to an AI model describing the task to perform.

Effective prompts improve consistency, accuracy, and response quality.

---

## Prompt Engineering

The practice of designing, testing, and refining prompts to improve AI performance without modifying the underlying model.

---

## Probabilistic System

A system whose outputs may vary even when given the same input.

Most Large Language Models are probabilistic systems.

---

## Precision / Recall

📊 Evaluation Metrics

Two of the most important metrics used to evaluate AI systems.

- **Precision** measures how many predicted positive results were actually correct.
- **Recall** measures how many actual positive cases were successfully identified.

Improving one often reduces the other, making the right balance a product decision rather than a purely technical one.

---

## PII (Personally Identifiable Information)

🔐 Privacy

Any information that can identify an individual, either directly or indirectly.

Examples include names, email addresses, phone numbers, national identification numbers, and home addresses.

Protecting PII is a fundamental requirement for responsible AI systems.

---

# R

## RAG (Retrieval-Augmented Generation)

A technique that combines information retrieval with language generation.

Instead of relying only on its training data, the model retrieves relevant information from external sources before generating a response.

---

## Re-ranking

A retrieval technique that improves search results by reordering retrieved documents according to relevance.

---

## Reinforcement Learning from Human Feedback (RLHF)

🧠 Training

A model training technique that uses human preferences to improve AI behavior after pretraining.

RLHF is widely used to make Large Language Models more helpful, truthful, and safe.

---

# S

## Semantic Search

A search method that retrieves information based on meaning rather than exact keyword matches.

Semantic search typically uses embeddings and vector databases.

---

## System Prompt

A high-level instruction that defines the behavior, personality, constraints, and objectives of an AI model throughout a conversation.

---

## Shadow Deployment

🚀 Deployment

A deployment strategy where a new AI model runs alongside the production model without exposing its outputs to users.

Shadow deployments allow teams to compare model performance safely before a full rollout.

---

## Supervised Learning / Unsupervised Learning

🧠 Machine Learning

Two primary approaches to machine learning.

- **Supervised Learning** uses labeled data with known correct answers.
- **Unsupervised Learning** discovers patterns or relationships in unlabeled data.

Each approach is suited to different types of problems.

---

# T

## Temperature

A model parameter controlling response randomness.

- Low temperature → More predictable responses
- High temperature → More creative responses

---

## Token

The basic unit of text processed by Large Language Models.

A token may represent a word, part of a word, punctuation, or a symbol.

Model pricing and context limits are usually measured in tokens.

---

## Tool Calling

A capability that allows AI models to invoke external functions or APIs to complete tasks.

Examples include checking the weather, querying databases, or sending emails.

---

# U

## User Prompt

The message or instruction provided by the end user during a conversation with an AI system.

---

# V

## Vector Database

A specialized database designed to store and search embeddings efficiently.

Popular vector databases include Pinecone, Weaviate, Milvus, Qdrant, and pgvector.

---

# X

## XAI (Explainable AI)

A collection of methods that help users understand how AI systems reach their decisions.

Explainability is particularly important in regulated industries such as healthcare, finance, and government.

---

# Z

## Zero-Shot Learning

📝 Prompt Engineering

A prompting approach in which the model performs a task without receiving any examples, relying entirely on the knowledge acquired during pretraining.

Zero-shot prompting is often the simplest way to prototype AI capabilities.

# Key Acronyms

The following acronyms appear frequently throughout this repository and are commonly used in AI Product Management, Machine Learning, Large Language Models (LLMs), Enterprise AI, and Product Development.

| Acronym | Full Form | Description |
|----------|-----------|-------------|
| AGI | Artificial General Intelligence | A theoretical AI capable of performing any intellectual task that a human can perform. |
| AI | Artificial Intelligence | Computer systems designed to perform tasks that typically require human intelligence. |
| API | Application Programming Interface | A standardized way for software applications to communicate with one another. |
| A/B Test | A/B Testing | An experiment that compares two versions of a feature or model to determine which performs better. |
| CoT | Chain of Thought | A prompting technique that encourages reasoning through intermediate steps before producing an answer. |
| DL | Deep Learning | A subset of Machine Learning based on deep neural networks. |
| ETL | Extract, Transform, Load | A process used to collect, clean, and move data into a data warehouse or other storage system. |
| F1 Score | F1 Score | The harmonic mean of Precision and Recall, commonly used to evaluate classification models. |
| GenAI | Generative AI | AI systems capable of generating new content such as text, images, audio, code, or video. |
| HITL | Human-in-the-Loop | A workflow where humans review, validate, or correct AI-generated outputs. |
| JSON | JavaScript Object Notation | A lightweight data format commonly used for structured communication between systems and AI models. |
| KPI | Key Performance Indicator | A measurable value used to evaluate business or product success. |
| LLM | Large Language Model | A large neural network trained to understand and generate human language. |
| LoRA | Low-Rank Adaptation | A parameter-efficient fine-tuning technique for adapting large AI models. |
| MCP | Model Context Protocol | An open protocol for connecting AI models with tools, resources, prompts, and external systems. |
| ML | Machine Learning | A branch of AI where models learn patterns from data rather than explicit programming. |
| MLOps | Machine Learning Operations | Practices for deploying, monitoring, and maintaining machine learning models in production. |
| NLP | Natural Language Processing | A field of AI focused on enabling computers to understand and generate human language. |
| NPS | Net Promoter Score | A customer satisfaction metric measuring users' likelihood of recommending a product. |
| OCR | Optical Character Recognition | Technology that converts images of text into machine-readable text. |
| OSS | Open Source Software | Software whose source code is publicly available for use and modification. |
| PII | Personally Identifiable Information | Information that can identify an individual and must be protected under privacy regulations. |
| PM | Product Manager | The person responsible for defining, building, and growing a product. |
| PRD | Product Requirements Document | A document describing a product's goals, requirements, features, and success criteria. |
| QA | Quality Assurance | The process of ensuring a product meets predefined quality standards before release. |
| RAG | Retrieval-Augmented Generation | A technique that combines information retrieval with Large Language Models to produce grounded responses. |
| RBAC | Role-Based Access Control | A security model where access permissions are assigned based on user roles. |
| REST | Representational State Transfer | A widely used architectural style for designing web APIs. |
| RLHF | Reinforcement Learning from Human Feedback | A model training technique that uses human preferences to improve AI behavior after pretraining. |
| SDK | Software Development Kit | A collection of tools, libraries, and documentation for building applications on a platform. |
| SLA | Service Level Agreement | A commitment defining expected service performance, availability, and response times. |
| SSO | Single Sign-On | An authentication method that allows users to access multiple applications using one login. |
| UI | User Interface | The visual elements through which users interact with a product. |
| UX | User Experience | The overall experience a user has while interacting with a product or service. |
| XML | Extensible Markup Language | A structured markup language sometimes used in prompt engineering and data exchange. |

---

> **This glossary is a living document.**
>
> As the AI ecosystem evolves, new concepts, models, frameworks, and terminology will be added to keep this repository current and useful.
