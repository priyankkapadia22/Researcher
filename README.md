# Researcher

An AI-powered Multi-Agent Research & Report Generation System built using LangGraph.

Researcher can generate comprehensive reports from either:

- 📄 Uploaded documents/files
- 🌐 Live web research on any topic

The system uses multiple AI agents working together to analyze content, perform research, collect resources, generate structured reports, and include relevant visual assets/images automatically.

---

# 🚀 Features

## 📄 Document-Based Research
- Upload PDFs, documents, or research material
- Extracts and analyzes content
- Generates structured reports automatically

## 🌐 Web Research Mode
- Enter any topic/query
- Performs web search for resources
- Collects and summarizes information
- Generates complete research reports

## 🤖 Multi-Agent Architecture
Built using LangGraph with multiple collaborative AI agents for:
- Planning
- Research
- Content extraction
- Summarization
- Critic evaluation
- Report generation
- Image/resource collection

## 🔄 Self-Correcting Workflow
Researcher includes a Critic Agent for quality validation and iterative refinement.

The generated content is evaluated based on:
- Topic relevance
- Content quality
- Completeness
- Structure
- Context alignment

If the critic score falls below the required threshold:
1. The planner agent re-plans the workflow
2. New research tasks are generated
3. Additional resources are collected
4. The research pipeline runs again
5. Improved content is generated

This creates a self-improving AI research pipeline capable of producing more accurate and topic-aligned reports.

## 🖼️ Automatic Image Integration
- Fetches relevant visuals/images
- Enhances generated reports visually

## 📝 Structured Report Generation
Generated reports may include:
- Introduction
- Key insights
- Technical analysis
- Visual content
- References/resources
- Conclusion

## ⚡ Automated Workflow
Complete end-to-end pipeline:
Input → Research → Analysis → Critic Evaluation → Refinement → Final Report

---

# 🧠 System Architecture


# 🛠️ Tech Stack

- LangGraph
- LangChain
- Python
- LLMs
- Web Search APIs
- Document Processing
- Multi-Agent AI Workflow
- AI Report Generation Pipeline

---

# 📂 Project Workflow

## 1️⃣ Upload File Mode

1. User uploads a file/document
2. System extracts text/content
3. Planner agent creates research strategy
4. Research agents analyze the document
5. Content writer generates report
6. Critic agent validates quality
7. If score is low → workflow re-runs
8. Images/resources are collected
9. Final report is generated

---

## 2️⃣ Topic Research Mode

1. User enters a research topic
2. Planner agent creates research tasks
3. Web research agent collects resources
4. Content is summarized and analyzed
5. Report writer generates structured content
6. Critic agent evaluates the report
7. If quality is low → workflow re-plans and retries
8. Images are fetched
9. Final research report is generated

---

# 🔑 Environment Variables

Create a `.env` file in the root directory.

Example:

```env
OPENAI_API_KEY=your_api_key
TAVILY_API_KEY=your_api_key
LANGCHAIN_API_KEY=your_api_key
```

Add all required API keys according to the services used in the project.

---

# ▶️ Run the Project

```bash
python app.py
```

or

```bash
streamlit run app.py
```

(Update according to your actual entry file.)

---

# 📸 Output

Generated reports may include:
- Structured research content
- Summaries
- Key findings
- AI-generated insights
- Visual references/images
- References and sources
- Topic-focused refined content
- Final report in PDF/MD format
- Citation & reference formatting
- Deep research mode

---

# 🎯 Use Cases

- Academic research
- Technical report generation
- Market research
- AI-assisted documentation
- Research summarization
- Automated knowledge extraction
- Deep topic analysis

---

# 🔮 Future Improvements

- Citation & reference formatting
- Real-time collaboration
- Memory-enabled agents
- Interactive report editing
- Custom templates
- Multi-language report generation

---
