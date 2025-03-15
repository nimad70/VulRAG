# VulRAG: Investigating LLM Vulnerabilities in RAG Systems

This repository accompanies the Master's thesis titled:

**"Security in Machine Learning: Exposing LLM Vulnerabilities through Poisoned Vector Databases in RAG-based Systems"**

The research focuses on the susceptibility of Large Language Models (LLMs) to misinformation within Retrieval-Augmented Generation (RAG) systems. It introduces poisoned data into vector databases and analyzes the resulting LLM responses to identify potential weaknesses and exploitation risks.

## Overview

Large Language Models (LLMs) have significantly advanced natural language processing tasks. However, their integration with Retrieval-Augmented Generation (RAG) systems introduces vulnerabilities, especially when external knowledge sources are compromised. This project examines how poisoning vector databases—integral components of RAG systems—affect LLM outputs, aiming to uncover and address security flaws.

## Objectives

- **Assess LLM Vulnerabilities**: Determine the impact of corrupted data within vector databases on LLM performance.
- **Analyze RAG System Security**: Investigate how RAG architectures can be exploited through data poisoning.
- **Develop Mitigation Strategies**: Propose methods to enhance the resilience of RAG-based LLM systems against such attacks.

## Methodology

1. **Data Poisoning**: Introduce malicious entries into vector databases used by RAG systems.
2. **LLM Evaluation**: Utilize state-of-the-art LLMs to process queries and observe the influence of poisoned data.
3. **Security Analysis**: Identify vulnerabilities and potential exploitation avenues within the RAG framework.
4. **Mitigation Development**: Formulate and test strategies to defend against identified threats.

## Repository Contents

- **Code**: Scripts and tools for poisoning vector databases and analyzing LLM responses.
- **Data**: Sample datasets for experimentation, including clean and poisoned versions.
- **Documentation**: Detailed explanations of methodologies, findings, and proposed countermeasures.

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nimad70/VulRAG.git

2. Explore the repository for scripts and data relevant to your experiments.

## License

VulRAG: Investigating LLM Vulnerabilities in RAG Systems © 2024 by Nima Daryabar is licensed under CC BY-SA 4.0 

## Citation

If you use this repository in your work, please cite it as follows:

```BibTeX
@thesis{daryabar2023security,
  title={Security in Machine Learning: Exposing LLM Vulnerabilities through Poisoned Vector Databases in RAG-based Systems},
  author={Nima Daryabar},
  institution={University of Padova},
  year={2023}
}
```

## Contact

For inquiries or collaboration opportunities, please contact:

- **Name**: Nima Daryabar
- **Email**: [nima daryabar](mailto:nima.daryabar@studenti.unipd.it)
- **GitHub**: [nimad70](https://github.com/nimad70)
