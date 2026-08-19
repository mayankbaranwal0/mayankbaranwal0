# Mayank Baranwal

**Full-stack and ML engineer. I ship AI systems where being wrong has consequences.**

Machine Learning Engineer at IF MedTech, working on agentic AI, computer vision and on-device ML in clinical products. 2.8+ years of production experience. Most of what I build sits between a model and a real user, so I spend as much time on evals, guardrails and failure handling as on the model itself.

Currently based in Bengaluru, India.

---

## What I work on

**[drskin.ai](https://drskin.ai/) · Agentic dermatology platform**
The agentic layer and the multi-model CV pipeline behind a live platform serving 70,000+ monthly active users. LangGraph triage state machines over WhatsApp, ReAct tool-calling agents scoped to bounded APIs, NL2Query as parameter synthesis instead of text-to-SQL, and Faster R-CNN plus U-Net detectors sharing a single MediaPipe Face Mesh pass. Every clinical agent ships behind shadow-mode evaluation against a dermatologist's independent decision before it goes live.

**MedRAG · Clinical RAG assistant**
Retrieval over 220+ clinical documents: semantic chunking, bge-m3 embeddings, hybrid dense + BM25 retrieval with cross-encoder reranking, and a LangGraph agent that rewrites queries and abstains when context is insufficient. Built its eval harness on LangSmith with a 110-item gold set, which moved recall@5 from 0.70 to 0.87 and faithfulness from 0.72 to 0.89.

**Intra-oral classification · On-device**
Fine-tuned ViT-Base/16 for 4-class intra-oral classification on 3,700+ clinical images, 0.81 macro-F1, INT8-quantized to ~165 MB at ~0.7 s/image on CPU, then migrated the runtime to ExecuTorch (PT2E).

**[Parivahan Mitra](https://www.vahanhelp.in/) · B2B logistics CRM**
Built solo end to end. Document and ID verification, Razorpay payments, WhatsApp integration, order and courier tracking. 430,000+ orders for 1,800+ users.

**Peck Dating · Consumer app**
React Native and Node.js, 30,000+ downloads. [App Store](https://apps.apple.com/in/app/peck-dating-app-match-date/id6469529163) · [Play Store](https://play.google.com/store/apps/details?id=com.fliptree.peck)

Before this I built on-device fall detection running on 7,000+ wearables and the SOS alerting stack around it.

---

## Stack

**Languages** Python · TypeScript / JavaScript · Go · Java · C++ · SQL

**Agentic & LLM** LangGraph · LangChain · LlamaIndex · CrewAI · Claude SDK · MCP · A2A · ReAct loops · tool calling · structured outputs · guardrails

**RAG** hybrid search (dense + BM25) · reranking · semantic-layer RAG · NL2Query · Pinecone · pgvector · Qdrant

**ML & CV** PyTorch · TensorFlow · scikit-learn · Hugging Face · ViT · YOLO · MediaPipe · OpenCV · LoRA / QLoRA · INT8 quantization · ExecuTorch

**Evals & MLOps** RAGAS · DeepEval · LangSmith · Langfuse · MLflow · Weights & Biases

**Backend & Web** FastAPI · Django · Node.js · Express · Next.js · React · HTML / HTMX · PostgreSQL · MongoDB · Redis

**Mobile** Flutter · React Native · Expo

**Infra** AWS · GCP · Docker · Kubernetes · Modal · RunPod · Airflow

---

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/mayankbaranwal-/) · [Email](mailto:mayankbaranwal95@gmail.com)

![Stats](https://github-readme-stats.vercel.app/api?username=mayankbaranwal0&show_icons=true&hide_border=true)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mayankbaranwal0&layout=compact&hide_border=true)
