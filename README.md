# 🛡️ AI Security Research

> Documenting my journey into AI/LLM security research, red teaming, and adversarial machine learning.

[![GitHub stars](https://img.shields.io/github/stars/samram77-art/ai-security-research?style=social)](https://github.com/samram77-art/ai-security-research/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/samram77-art/ai-security-research)](https://github.com/samram77-art/ai-security-research/commits/main)

## 👋 About

I'm a security researcher focused on **Large Language Model (LLM) security**, prompt injection, jailbreaking techniques, and adversarial AI. This repo documents my hands-on learning, experiments, and findings.

## 🎯 Focus Areas

- 🔓 **Prompt Injection** — Direct & indirect attacks
- 🚫 **Jailbreak Techniques** — Bypassing safety guardrails
- 🔍 **Model Reconnaissance** — Fingerprinting & profiling
- 💉 **Data Extraction** — PII leakage, training data extraction
- 🤖 **Multi-turn Attacks** — Conversation-level exploitation
- 🛠️ **Tooling** — Custom Python scripts for AI red teaming

## 📂 Repository Structure

| Folder | Description |
|--------|-------------|
| [`/scripts`](./scripts) | Custom Python tools for AI pentesting |
| [`/writeups`](./writeups) | Detailed analyses of vulnerabilities found |
| [`/reports`](./reports) | Sample pentest reports & findings |
| [`/docs`](./docs) | Methodology notes & learnings |
| [`/resources`](./resources) | Cheatsheets, references, useful links |

## 🚀 Featured Projects

### 🔬 LLM Pentest Suite
A modular Python toolkit for testing LLM endpoints:
- Model reconnaissance & fingerprinting
- Automated prompt injection testing
- Jailbreak technique scanner
- Multi-turn attack chains
- HTML report generation

[→ View the suite](./scripts)

### 📊 Llama 3.2 Security Assessment
Comprehensive security analysis of Meta's Llama 3.2 (1B) running locally via Ollama.

**Key findings:**
- 37.5% jailbreak success rate (3/8 techniques)
- Token smuggling via base64 encoding bypassed
- "Developer Mode" persona injection successful
- Strong defenses against classic attacks (DAN, Grandma exploit)

[→ Read full writeup](./writeups/llama32-assessment.md)

## 🎓 Skills & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

**Frameworks I use:** OWASP LLM Top 10, MITRE ATLAS, NIST AI RMF

**Tools:** Custom Python tooling, Garak, PyRIT, Promptfoo, Ollama

## 📚 Learning Resources

I curate a list of high-quality AI security resources here:
[→ View resources](./resources/README.md)

## 📝 Recent Writeups

- **[Llama 3.2 Security Assessment](./writeups/llama32-assessment.md)** — Multi-vector security analysis with 61% bypass rate

## 🤝 Connect

- 🐙 [GitHub](https://github.com/samram77-art)

---

⚠️ **Disclaimer:** All research conducted in this repository is performed on systems I own or have explicit authorization to test. This work is for educational and defensive security purposes only.
