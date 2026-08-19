# Mayank Baranwal

**AI / ML engineer. I ship AI systems where being wrong has consequences.**

Machine Learning Engineer at IF MedTech, working on agentic AI, computer vision and on-device ML in clinical products. 2.8+ years of production experience. Most of what I build sits between a model and a real user, so I spend as much time on evals, guardrails and failure handling as on the model itself.

Currently based in Bengaluru, India.

**What I work on**

- Agentic systems: LangGraph, LangChain, MCP, A2A, Claude SDK, tool-calling agents, state machines
- RAG and retrieval: hybrid search (dense + BM25), reranking, chunking strategy, NL2Query, Pinecone, pgvector
- Eval infrastructure: RAGAS, LangSmith, gold datasets, CI regression runs, shadow-mode promotion gates
- Vision: PyTorch, ViT, YOLO, MediaPipe, fine-tuning, INT8 quantization, ExecuTorch, on-device inference
- Full-stack around it: FastAPI, Node.js, Next.js, HTML/HTMX, Flutter, AWS, Docker, CI/CD

**Some things I've shipped**

- Agentic layer and multi-model CV pipeline behind [drskin.ai](https://drskin.ai/), serving 70,000+ monthly active users: LangGraph WhatsApp triage, ReAct agents scoped to bounded APIs, Faster R-CNN and U-Net detectors sharing one MediaPipe Face Mesh pass
- Agentic RAG assistant over 220+ clinical documents; eval harness took recall@5 from 0.70 to 0.87 and faithfulness from 0.72 to 0.89, with a self-check node that abstains when context is insufficient
- On-device fall detection running on 7,000+ devices within 8 months: 83% sensitivity at 1.7 false alarms/day in continuous wear, inference on the MCU with belt and chest mounting and two caregiver-selectable sensitivity profiles
- ViT-Base/16 fine-tuned for 4-class intra-oral classification (0.81 macro-F1 on 3,700+ clinical images), INT8-quantized to ~165 MB at ~0.7s/image on-device, runtime migrated to ExecuTorch
- [Parivahan Mitra](https://www.vahanhelp.in/), a B2B logistics CRM built solo end to end and live in production: 430,000+ orders for 1,800+ users
- [Peck Dating](https://apps.apple.com/in/app/peck-dating-app-match-date/id6469529163), a React Native consumer app with 30,000+ downloads ([Play Store](https://play.google.com/store/apps/details?id=com.fliptree.peck))

**Reach me:** [X](https://x.com/mayankbaranwal_) · [LinkedIn](https://www.linkedin.com/in/mayankbaranwal-/) · mayankbaranwal95@gmail.com

![Stats](https://github-readme-stats.vercel.app/api?username=mayankbaranwal0&show_icons=true&hide_border=true)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mayankbaranwal0&layout=compact&hide_border=true)
