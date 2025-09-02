# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
## DATE:
## AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

---

## Scenario:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on **“The Basics of Blockchain Technology”** using multiple AI platforms and prompting strategies.

The goal is to determine which **combination of prompting technique + platform** provides the best summary in terms of:

* **Accuracy** (factual correctness)
* **Coherence** (logical flow)
* **Simplicity** (easy for undergraduates)
* **Speed** (response time)
* **User Experience** (ease of prompting and readability)

---

## Algorithm:

1. **Dataset Preparation**

   * Select a 500-word technical article on *The Basics of Blockchain Technology*.
   * Ensure article covers fundamentals: definition, working, features, applications, limitations.

2. **Prompting Techniques Setup**

   * **Zero-Shot Prompt** → “Summarize the following article in simple terms for undergraduate students.”
   * **Few-Shot Prompt** → Provide 2–3 sample summaries of other tech articles, then ask model to summarize blockchain article.
   * **Chain-of-Thought Prompt** → “Summarize step by step: first identify main ideas, then condense into a student-friendly summary.”
   * **Role-Based Prompt** → “You are a university professor. Summarize this article in simple terms for undergraduate students.”

3. **Platform Selection**

   * Use four AI platforms: **ChatGPT, Gemini, Claude, GitHub Copilot**.
   * Run each of the four prompting techniques on each platform.

4. **Execution**

   * Collect summaries generated (16 outputs total).
   * Record response time and user experience (ease of use, clarity).

5. **Evaluation Metrics**

   * **Accuracy** → Check factual correctness vs source text.
   * **Coherence** → Evaluate logical structure of summary.
   * **Simplicity** → Rate readability for undergraduate students.
   * **Speed** → Measure time taken per response.
   * **User Experience** → Subjective rating (ease of prompt formulation, clarity of results).

6. **Comparison & Analysis**

   * Create a comparative table of results.
   * Identify best performing **prompt + platform** combination.

---

## Result:

Thus the Prompting tools are executed and analysed sucessfully .

---
