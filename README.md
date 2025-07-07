# Agentic AI Blog Generator

> An intelligent blog writing assistant powered by **LangGraph**, **Tavily**, and **Groq**.  
> Give it a topic, and it’ll research, draft, evaluate, and improve a full-length blog post automatically.  
> Also generates a downloadable `.docx` version of the final blog so you can make any edits.

## Live Demo
👉 Try it now: [**Agentic AI Blog Generator App**](https://agentic-ai-blog-generator.streamlit.app/)  
No setup needed — just plug in your Groq API key and your favourite Groq model to start generating blogs.

## Workflow Diagram (LangGraph Flow)
![image](https://github.com/user-attachments/assets/7db0f9f9-39a9-4bd7-b7a9-6ce78fb84818)

## Features
- **Web Research**: Automatically gathers the latest insights using Tavily search API.
- **Smart Drafting**: Crafts an informative, structured, and engaging blog post using a Groq LLM.
- **Strict Quality Evaluation**: Performs a 6-point quality check for length, clarity, value, and structure.
- **Automatic Revisions**: If the draft fails, it’s improved until it meets the criteria.
- **Docx Export**: Final blog is generated as a Word document for easy sharing.
- **Agentic Architecture**: Uses LangGraph’s conditional edge system for dynamic control flow.

## Tech Stack
- `Streamlit` – frontend UI
- `LangGraph` – orchestrates the agentic workflow
- `LangChain` – wraps LLMs and tool usage
- `Groq` – blazing-fast LLM backend
- `Tavily` – for real-time web search
- `python-docx` – for `.docx` file generation
- `dotenv` – secure API key management
