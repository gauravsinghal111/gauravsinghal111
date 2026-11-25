# Hi, I'm Gaurav Singhal 👋

### Building AI systems · MS AI Carnegie Mellon University · IIT Dharwad

I'm a Master's Artificial Intelligence Engineering student at Carnegie Mellon University. I like building end-to-end systems — from retrieval pipelines to deployed web apps — and I care a lot about making ML actually work in the real world, not just in notebooks.

---

### 🧩 Projects

**[AI Security: Red-Teamed Agentic Research Platform](https://github.com/gauravsinghal111/REPO-NAME-1)**
- Ran 14 red-team prompts (jailbreaks, prompt injection, crescendo) through Microsoft PyRIT to find security gaps.
- Added AWS Bedrock Guardrails to check every request and reply, blocking prompt attacks, harmful content and personal data like card numbers.
- Built 4 LangGraph agents that search, summarize, write and review reports, with TensorZero falling back from GPT-4o to Groq when it fails.
- Deployed on AWS ECS with API keys and rate limiting (10 requests/min), using LangSmith to score every report for hallucination risk.

`Python` `LangGraph` `PyRIT` `AWS Bedrock` `TensorZero` `LangSmith` `Redis` `AWS ECS` `Terraform`

**[Secure Enterprise Agentic RAG](https://github.com/gauravsinghal111/REPO-NAME-2)**
- Built a LangGraph RAG agent on GCP that filters noisy data from real documents using Qdrant and FlashRank re-ranking.
- Added NeMo Guardrails to block jailbreaks and prompt injection, and tested how many attacks they caught.
- Routed LLM calls through a Portkey gateway with backup models, scored answers with RAGAS and deployed on Cloud Run.

`Python` `LangGraph` `NeMo Guardrails` `Portkey` `RAGAS` `Qdrant` `GCP Cloud Run` `Vertex AI`

**[DocAgent: Intelligent Document Processing AI Agent](https://github.com/gauravsinghal111/REPO-NAME-3)**
- Added OCR for scanned PDFs and photos with a vision-model fallback, plus rule-based checks for 6 error types alongside LLM review.
- Built a 73-document synthetic test set; a regex baseline scored 89.7% accuracy and 77.7% extraction F1.
- Fixed broken Langfuse tracing, moved off retired Groq models, cut LLM calls per chat message from 3N+1 to 1, and added 34 automated tests.

`Python` `LangGraph` `Groq` `Tesseract` `Langfuse` `FastAPI` `NumPy` `SciPy`

**[RAG-based AI Teaching Assistant](https://github.com/gauravsinghal111/RAG-based-AI-Teaching-Assistant)**
Built a retrieval-augmented generation system from scratch — custom chunking, embedding, vector search, and an answer-generation layer using Whisper + Llama.

`Python` `Whisper` `LLMs`

---

### 🛠️ Tech Stack

**Languages:** Python · SQL · JavaScript · TypeScript

**ML / AI:** scikit-learn · PyTorch · RAG pipelines · LangGraph · Whisper · Llama · embeddings

**AI Security & Evals:** PyRIT · AWS Bedrock Guardrails · NeMo Guardrails · RAGAS · LangSmith · Langfuse

**Infra & Tools:** AWS ECS · GCP Cloud Run · Terraform · Redis · Qdrant · FastAPI · Next.js · Vercel · Git

---

### 🤝 Let's connect

[LinkedIn](https://www.linkedin.com/in/gaurav-singhal-5b0805265/) · [Portfolio](https://gauravsinghalportfolio.vercel.app)
