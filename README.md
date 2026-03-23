# 🤖 The Autonomous Agentic AI Framework: From Creation to Goal Execution  
### A Framework for Autonomous Multi-Agent Systems

---

## 📊 Overview

This project presents an **autonomous multi-agent AI framework** built using **CrewAI**, designed to simulate end-to-end task execution through collaborative intelligent agents.

The system demonstrates how multiple specialized agents can work together to:
- Gather information
- Generate structured content
- Validate outputs
- Correct errors
- Refine results
- Analyze system performance

Using an **iterative 3-stage pipeline**, the framework improves output quality over time and visualizes performance progression, showcasing **convergence behavior in autonomous systems**.

---

## 🚀 Features

- 🤖 Multi-Agent Collaboration (Researcher, Writer, Verifier, Analyst)
- 🔁 Iterative Workflow (Generation → Correction → Refinement)
- 📈 Custom Quality Scoring System
- 📊 Performance Visualization using Matplotlib
- ✅ Automated Verification & Self-Correction
- 🧠 AI-driven Workflow Analysis
- 🔍 Keyword-based Content Evaluation

---

## 🏗️ Project Structure
.
├── main.py # Main execution script
├── agentic_quality_curve_final.png # Generated performance graph
├── requirements.txt # Project dependencies
├── .env # Environment variables (API key)
└── README.md # Documentation

---

## ⚙️ Workflow Explanation

The framework operates through a **sequential multi-agent pipeline**:

1. **Research Phase**
   - Researcher agent gathers relevant information.

2. **Initial Writing Phase**
   - Writer agent generates a report (without title).

3. **Verification Phase**
   - Verifier checks:
     - Presence of title
     - Topic correctness

4. **Correction Phase**
   - If errors exist, Writer corrects structure (adds title).

5. **Refinement Phase**
   - Writer enhances:
     - Depth
     - Clarity
     - Coverage (vaccination, variants, etc.)

6. **Analysis Phase**
   - Analyst evaluates improvement across iterations.

7. **Visualization**
   - Graph shows quality score progression.

---

## 🔄 Iterations Overview

| Attempt | Phase        | Description                          |
|--------|-------------|--------------------------------------|
| 1️⃣     | Initial     | Generates base report                |
| 2️⃣     | Correction  | Fixes structural issues (title, etc.)|
| 3️⃣     | Refinement  | Enhances depth, clarity, completeness|

---

## 📊 Quality Evaluation

The system uses a **custom scoring function** to evaluate report quality:

### Evaluation Criteria:
- ✅ Presence of Title
- ✅ Verification Status
- 📏 Word Count
- 🧠 Sentence Complexity
- 🔑 Keyword Coverage:
  - lockdown
  - vaccination
  - variant
  - wave
  - testing
  - healthcare
- 🎯 Refinement Bonus
- 🎲 Controlled Randomness

**Score Range:** 50 – 95

---

## 📈 Output

### 📝 Generated Reports
- Initial Report  
- Corrected Report  
- Refined Final Report  

### 📊 Performance Graph
agentic_quality_curve_final.png


**Graph Shows:**
- Iteration Number vs Quality Score
- Improvement Trend
- Convergence Behavior

---

## 🧠 Agents in the System

| Agent        | Role |
|-------------|------|
| Researcher  | Collects factual information |
| Writer      | Generates and improves reports |
| Verifier    | Validates correctness and structure |
| Analyst     | Explains workflow improvements |

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sujal-SM/agentic-ai-framework.git
cd agentic-ai-framework
```
### Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows
```
### Setup Environment Variables
```bash
Create a .env file:

OPENAI_API_KEY=your_api_key_here
```

📜 License

This project is licensed under the MIT License.