## Sai Bharadwaj Cheruvu

Azure AI Engineer in Melbourne. I build agents that answer from real sources, and the evaluation harnesses that show whether they actually do.

Right now I'm building the AI platform at a Melbourne travel operator: a shared agent layer on Azure AI Foundry sitting behind a voice call bot, website and WhatsApp assistants, and internal knowledge retrieval. Most of the work is the unglamorous half — grounding, guardrails, tool boundaries, and the regression suite that has to pass before a prompt change ships.

Before AI I worked on embedded systems and hardware QA. That background is why I reach for a test harness before a demo.

### Projects

**[azure-ai-agent-eval](https://github.com/sai-cheruvu/azure-ai-agent-eval)** — A grounded Azure OpenAI agent with the evaluation suite that proves it works. Hybrid BM25 and vector retrieval fused with RRF, a grounding gate that makes the agent refuse rather than improvise, and a golden set wired into CI. Runs end to end with no Azure key, so the suite is a real gate on every pull request.

**[graph-agent-toolkit](https://github.com/sai-cheruvu/graph-agent-toolkit)** — Microsoft Graph as agent tools, with least privilege enforced in code rather than trusted to the prompt. Scopes checked against the token's real claims, writes off by default, audit log with message bodies redacted.

**[agent-telemetry](https://github.com/sai-cheruvu/agent-telemetry)** — Span tracing, token accounting and budget ceilings for agent runs. No dependencies, and the clock is injected so timing is testable without sleeps.

### Certifications

Microsoft Certified: Azure AI Engineer Associate (AI-102), Azure AI Fundamentals (AI-900), Azure Fundamentals (AZ-900). AZ-104 in progress.

Engineers Australia — Certified Electronics Engineer.

### Contact

[LinkedIn](https://www.linkedin.com/in/sai-cheruvu) · sai.b.cheruvu@gmail.com

Open to Azure AI and AI engineering roles in Melbourne.
