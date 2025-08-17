**PPT-QA System**

A portfolio ML/NLP project that automates slide summarization and enables question answering from PowerPoint and PDF presentations. Designed as a demonstration of practical document intelligence workflows using state-of-the-art transformer models.

🔹 **Project Overview**

Modern organizations generate hundreds of slides and reports. Manually scanning them is time-consuming. This project shows how Natural Language Processing can be applied to:

Extract content from PowerPoint and PDF files

Summarize presentations with Hugging Face’s BART model

Enable interactive Q&A on the slide content using LLaMA (via transformers)

Build a pipeline that runs end-to-end on Google Colab

**Tech Stack**

Python (Google Colab as execution environment)

Libraries:

Hugging Face Transformers – Summarization (BART) & Q&A (LLaMA)

PyPDF2 – Extract text from PDFs

**Workflow**

Upload PPT/PDF to Colab

Extract text with python-pptx / PyPDF2

Summarize slides using BART (facebook/bart-large-cnn)

Ask questions about the presentation with LLaMA 3B-Instruct

Output: Concise summaries and context-aware answers

**Example Use Cases**

Quickly summarize a 100+ slide deck into key insights

Interactive Q&A during presentation prep (e.g., “Which slides mention budget allocation?”)

Research/learning support for long PDF reports

**Future Extensions 🚀**

Deploy with Streamlit/Gradio for a user-friendly app

Add vector database integration (e.g., FAISS, Pinecone) for scalable retrieval

Expand to other document types (Word, Excel)

**Author**

Developed by Geowin Varghese (GitHub: Raw-Fox)

python-pptx – Parse and extract slide content

Additional utils – text preprocessing, context handling
