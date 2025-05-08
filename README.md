# LLM-Eval-Pipeline

This project implements a full evaluation pipeline for comparing large language models (LLMs) in a career-readiness domain. Inspired by platforms like Handshake, the pipeline assesses how well LLMs respond to job-seeker queries using both reference-based and reference-free metrics.

## Use Case

Evaluate LLM-generated responses to prompts such as:
- “How should I tailor my resume for a software engineering internship?”
- “What are common mistakes in a job application?”

These questions reflect real-world user pain points in the early-career job search space.

## Tech Stack

- **LangChain** for LLM orchestration
- **Google Gemini (via LangChain-Google)** for inference and evaluation
- **Pandas + Matplotlib** for data wrangling and visualization
- **Evaluation Criteria**: Correctness, Relevance, Coherence, Conciseness
- **Pairwise Comparison Module**: LLM-as-judge to simulate human feedback

## Output

- Side-by-side model comparisons
- Bar and radar charts visualizing average scores
- CSV exports of scores and detailed model outputs

## What This Shows

- Ability to build LLM evaluation systems with human-in-the-loop components
- Prompt engineering and judgment scoring for domain-specific use cases
- End-to-end data pipeline execution for AI product evaluation
