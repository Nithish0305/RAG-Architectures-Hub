\# 🤖 Project 03: Fully Automated RAG with n8n \& Pinecone



This project demonstrates a production-ready, low-code RAG (Retrieval-Augmented Generation) pipeline. It handles both the \*\*Data Ingestion (ETL)\*\* and the \*\*Chat Interface\*\* within a single automated workflow.



\### 🛠️ Tech Stack

\* \*\*Orchestration:\*\* n8n (Low-code Automation)

\* \*\*LLM:\*\* Groq (Llama 3 / Mixtral)

\* \*\*Embeddings:\*\* OpenAI `text-embedding-3-small`

\* \*\*Vector Database:\*\* Pinecone (Serverless)

\* \*\*Frontend:\*\* Custom HTML/JS Chat Widget (included)



\### 🚀 Setup Instructions

1\.  \*\*Import Workflow:\*\* Open n8n and import the `workflow.json` file.

2\.  \*\*Credentials:\*\* Set up your API keys in n8n for:

&#x20;   \* Groq Cloud

&#x20;   \* OpenAI

&#x20;   \* Pinecone

3\.  \*\*Deploy Webhook:\*\* Click "Execute Workflow" or "Activate" to get your \*\*Production Webhook URL\*\*.

4\.  \*\*Frontend Setup:\*\* \* Open `index.html`.

&#x20;   \* Replace `YOUR\_N8N\_PRODUCTION\_WEBHOOK\_URL\_HERE` with your actual URL.

&#x20;   \* Open `index.html` in any browser to chat with your documents.



\### 💡 Key Features

\* \*\*Scalability:\*\* Uses Pinecone for high-performance vector retrieval.

\* \*\*Speed:\*\* Groq inference ensures near-instant chat responses.

\* \*\*Embeddable:\*\* The provided HTML widget can be dropped into any website or portfolio.

