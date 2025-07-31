# IBM-cloud

# 🧠 Retrieval-Augmented Generation with Agentic AI on IBM Cloud

This project demonstrates how to deploy a Retrieval-Augmented Generation (RAG) pipeline using **Watsonx.ai** and **Agentic AI tools** on **IBM Cloud**. It combines foundational AI capabilities with dynamic document retrieval, vector indexing, and agent deployment workflows.

---

## 📌 Overview

- 🔍 **RAG (Retrieval-Augmented Generation)** uses external document context to improve response accuracy.
- 🤖 **Watsonx Agentic AI** enables no-code deployment of intelligent agents powered by foundation models.
- ☁️ **IBM Cloud** serves as the platform for deploying vector indices, knowledge bases, and AI models.

---

## 📁 Contents

- `RAG deployment.ipynb` — Implementation of RAG pipeline logic (document upload, embedding, retrieval).
- `Agentic AI on IBM Cloud.pdf` — Full step-by-step IBM Cloud deployment walkthrough.
- `README.md` — You are here.

---

## 🚀 Features

- Upload and index documents (PDF/TXT) into vector stores.
- Use Mistral or other foundation models via Watsonx Studio.
- Ask contextual questions with answers grounded in your documents.
- Deploy AI agents with tools and knowledge bases.
- Preview agents and access API endpoints from IBM Cloud UI.

---

## 🧱 Technologies Used

| Technology        | Purpose                                       |
|-------------------|-----------------------------------------------|
| IBM Watsonx.ai     | Agent interface + model selection             |
| Cloud Object Storage | Document storage (Lite Plan recommended)   |
| RAG Pipeline       | Context retrieval and LLM response generation |
| Vector Index       | Semantic embedding of document chunks         |
| Mistral Foundation Model | Deployed model for generative answering  |

---

## 📊 Step-by-Step: Agentic AI Deployment on IBM Cloud

### 1. Setup Watsonx Project

1. Login at [cloud.ibm.com](https://cloud.ibm.com)
2. Search for **Watsonx.ai Studio**
3. Select region as `London`, click **Create**
4. Click "Create a Sandbox Project"
5. Add storage using Cloud Object Storage (Lite plan is free)

### 2. Associate Services

6. Click **Manage > Services & Integrations > Associate Service**
7. Create a **watsonx.ai Runtime**
8. Associate it with the project

### 3. Build and Configure Agent

9. Click on **Build AI Agent to Automate Tasks**
10. Choose foundation model (e.g. `Mistral Large`)
11. Upload your document(s) to create a **Vector Index**
12. Enable tools like "Retrieve" or "Upload"
13. Test your question-answering interface

### 4. Deploy Your Agent

14. Click **Save** and assign an agent name
15. Open **Deployment Spaces > Create New**
16. If blocked, delete old deployments first
17. Deploy the agent and click **View Status**
18. Once deployed, access the **API Reference**

---

## 🧪 Example Use Case

Upload a document titled `Introduction to RAG`. After indexing, ask:
> *"How does RAG reduce hallucinations in LLMs?"*

Expected output:
> “RAG integrates external knowledge retrieval, reducing hallucinations by grounding answers in actual documents.”

---

## 📷 Screenshots

_Note: For visual steps, refer to the included PDF guide._

---

## 🧩 Future Improvements

- Add LangChain integration
- Enable document summarization pre-index
- Fine-tune foundation model responses via RLHF

---

## 🧑‍💻 Authors

- Aryan Gupta  
- Built as part of IBM Cloud RAG + Agentic AI experimentation

---

## 📄 License

This project is licensed under the MIT License.
