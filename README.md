# EX-02: Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization

## Register Number : 212223040188

---

## AIM
To evaluate and compare the effectiveness of various prompting techniques (zero-shot, few-shot, chain-of-thought, role-based, tabular, and comparative) across multiple state-of-the-art AI platforms (e.g., ChatGPT, Claude, Gemini/Bard, Cohere Command, and Meta AI) for text summarization, technical reasoning, and structured task execution.

---

## ALGORITHM

1. **Define the Use Case:** Select a uniform suite of evaluation tasks applicable across all candidate platforms (e.g., direct Q&A, table generation, comparative synthesis, and step-by-step guidance).
2. **Design Standardized Prompts:** Construct precise, consistent prompt templates across 8 distinct prompting categories to ensure unbiased baseline testing across models.
3. **Execute Cross-Platform Runs:** Input the standardized prompts into each AI tool (ChatGPT, Claude, Gemini/Bard, Cohere Command, and Meta AI) under identical input conditions.
4. **Evaluate Output Quality:** Assess performance across four core metrics:
   * **Accuracy:** Correctness and factual precision of the response.
   * **Clarity:** Readability, tone, and logical flow.
   * **Depth:** Comprehensiveness and detail level provided.
   * **Relevance:** Direct adherence to the prompt's instructions and constraints.
5. **Analyze & Benchmark:** Synthesize performance metrics into a comparative evaluation matrix to identify model strengths, formatting capabilities, and context handling limits.

---

## EXPERIMENTAL PROMPTS & CROSS-PLATFORM EXECUTIONS

### 1. Straightforward Prompting (Zero-Shot Baseline)
> **Prompt:** `"What is the capital of France?"`

* **ChatGPT:** The capital of France is Paris.
* **Claude:** Paris is the capital of France.
* **Gemini / Bard:** The capital of France is Paris.
* **Cohere Command:** Paris is the capital of France.
* **Meta AI:** The capital of France is Paris.

---

### 2. Tabular Format Prompting
> **Prompt:** `"Create a table comparing the key features of AI models."`

| AI Platform | Representative Response Format |
| :--- | :--- |
| **ChatGPT** | Feature \| Natural Language Understanding \| Contextual Memory \| Availability \| Speed |
| **Claude** | Feature \| Natural Language Understanding \| Processing Speed \| Data Usage |
| **Gemini / Bard** | Feature \| Contextual Understanding \| Response Speed \| Availability |
| **Cohere Command**| Feature \| Speed \| Contextual Understanding \| Integration Options |
| **Meta AI** | Feature \| Contextual Understanding \| General Performance \| Accessibility |

---

### 3. Missing Word (Fill-in-the-Blank) Prompting
> **Prompt:** `"The capital of Italy is ___."`

* **ChatGPT:** The capital of Italy is Rome.
* **Claude:** The capital of Italy is Rome.
* **Gemini / Bard:** The capital of Italy is Rome.
* **Cohere Command:** The capital of Italy is Rome.
* **Meta AI:** The capital of Italy is Rome.

---

### 4. Preceding Question / Context Conditioning
> **Prompt:** `"Given that the capital of France is Paris, what is the capital of Italy?"`

* **ChatGPT:** The capital of Italy is Rome.
* **Claude:** The capital of Italy is Rome.
* **Gemini / Bard:** The capital of Italy is Rome.
* **Cohere Command:** The capital of Italy is Rome.
* **Meta AI:** The capital of Italy is Rome.

---

### 5. Comparative Analysis Prompting
> **Prompt:** `"Compare the features of Python and Java."`

* **ChatGPT:** Python focuses on simplicity and rapid development, making it ideal for beginners and AI/data science. Java offers strong typing, object-oriented rigor, and high performance for large-scale enterprise systems.
* **Claude:** Python prioritizes code readability and speed of execution in scripting, whereas Java excels in enterprise scalability, multi-threading, and robust memory management.
* **Gemini / Bard:** Python is highly versatile and beginner-friendly with extensive libraries. Java is structured, robust, and preferred for building secure, high-concurrency enterprise applications.
* **Cohere Command:** Python provides flexibility and fast prototyping. Java provides rigid structure and better performance in large distributed systems.
* **Meta AI:** Python is easier to learn and write, while Java is more robust and better suited for heavy enterprise software.

---

### 6. Experiential & Cognitive Perspective Prompting
> **Prompt:** `"What is the best way to improve focus while studying?"`

* **ChatGPT:** Create a quiet workspace, use time-blocking methods like the Pomodoro Technique, break complex topics into smaller chunks, stay hydrated, and take structured breaks.
* **Claude:** Optimize your environment, define explicit study goals per session, and employ active recall alongside spaced repetition while eliminating digital distractions.
* **Gemini / Bard:** Build a distraction-free setup, practice mindfulness routines, set clear targets, and balance effort with systematic breaks and proper rest.
* **Cohere Command:** Limit surrounding distractions, apply the Pomodoro framework, organize study materials in advance, and maintain regular break schedules.
* **Meta AI:** Remove immediate distractions, adhere to a strict daily schedule, and take short, routine breaks to keep your mind sharp.

---

### 7. Everyday Functioning & Instructional Guidance
> **Prompt:** `"How do I prepare for a job interview?"`

* **ChatGPT:** Research the organization and role, practice answering common STAR-format questions, refine your resume, dress appropriately, and ensure punctual arrival.
* **Claude:** Deeply investigate company values and requirements, rehearse targeted responses showcasing your skills, align professional attire, and arrive ahead of time.
* **Gemini / Bard:** Review role details, prepare specific past examples demonstrating core competencies, practice common interview scenarios, dress professionally, and arrive early.
* **Cohere Command:** Conduct company research, practice core responses, select business-appropriate attire, and ensure strict punctuality.
* **Meta AI:** Research the hiring company, prepare clear answers to common questions, dress professionally, and show up early to make a strong initial impression.

---

### 8. Universal Technical Explanation
> **Prompt:** `"Explain the process of machine learning in simple terms."`

* **ChatGPT:** Machine learning is a way of teaching computers to learn from data to identify patterns and make decisions automatically, improving over time without being explicitly programmed for every scenario.
* **Claude:** Machine learning feeds observational data into algorithms, enabling systems to recognize underlying patterns, learn from experience, and generate predictions or decisions.
* **Gemini / Bard:** Machine learning involves systems analyzing vast datasets to uncover patterns, which they then use to draw conclusions or forecast outcomes on unseen data.
* **Cohere Command:** Machine learning refers to algorithms discovering statistical patterns within data to make automated predictions, growing more accurate as data volume increases.
* **Meta AI:** Machine learning is a technique where computers process data, uncover hidden trends, and apply those insights to make accurate future decisions.

---

## CROSS-PLATFORM PERFORMANCE EVALUATION MATRIX

| Prompt Style / Criteria | ChatGPT | Claude | Gemini / Bard | Cohere Command | Meta AI |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Straightforward Queries** | Highly precise & immediate | Clear and concise | Fast and accurate | Direct, minimal fluff | Accurate and simple |
| **Tabular Output Generation** | Native Markdown table mastery | Moderate, layout varies | Strong, occasional omissions | Basic structural formatting | Simple tables only |
| **Fill-in-the-Blank Context** | Strong contextual retention | Accurate completion | Excellent context matching | Solid short-context fit | Reliable for short blanks |
| **Chained Context Prompts** | Robust multi-turn memory | Solid contextual tracking | Effective short-range memory | Handles concise chains well | Variable on extended chains |
| **Comparative Synthesis** | In-depth, well-balanced | Structural pros/cons focus | Comprehensive & clear | Short, high-level summary | Basic comparison points |
| **Experiential Guidance** | Empathetic & actionable | Methodical & cognitive | Practical & real-world | Direct & factual | General baseline advice |
| **Instructional Workflows** | Detailed, step-by-step | Structured & pragmatic | Actionable with examples | Functional & straightforward | Reliable basic steps |
| **Technical Explanations** | Versatile for any audience | Clear conceptual focus | Strong analogies & examples | Concise overview | Clear, low technical depth |
| **Complex/Large Inputs** | Exceptional context handling | Strong long-context parsing | Good medium-length handling | Efficient summary, less depth | Good on standard lengths |

---

## RESULT
The prompting strategies across all designated AI platforms (**ChatGPT**, **Claude**, **Gemini/Bard**, **Cohere Command**, and **Meta AI**) were systematically designed, executed, evaluated, and documented in repository `https://github.com/RaajaThilahar/Ex.No.2.git`.
