<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./banner-light.svg">
  <img alt="Jayaragul N — AI engineer" src="./banner-dark.svg">
</picture>

AI engineer in Coimbatore, India. I build across the whole stack — language models and agentic
systems, the backends and APIs that serve them, computer vision, data science, and the
occasional robot. I try to understand a problem and its domain properly before I start building.

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./capabilities-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./capabilities-light.svg">
  <img alt="Capability map across five engineering domains" src="./capabilities-dark.svg">
</picture>

---

### What I build

**AI agents** — this is where most of my work lives. Systems that classify intent, pick tools,
call them, and reason over the results in structured steps rather than one-shot prompting:
a factory copilot for inventory and risk reporting, a healthcare assistant built behind
guardrails, an industrial data agent with sandboxed code execution, and a Mixture-of-Experts
platform that routes queries to specialised experts over shared memory. Roughly a dozen of my
repos are agents of one kind or another.

**Language models** — I don't stop at calling an API. I've fine-tuned small models on private
data and written a **27.8M-parameter GPT from scratch** in PyTorch — attention, tokenizer and
training loop by hand — to understand what's actually happening inside one.

**Backends & full stack** — Django and Flask services, REST APIs, SQL and MongoDB, deployed and
running. Most of my AI work ships behind an endpoint someone can actually call.

**Computer vision** — CNN classifiers for medical imaging and real-time detection, built with
OpenCV and TensorFlow.

**Data science** — cleaning messy real-world data, training models, and putting them behind
interfaces non-technical people can use.

**Robotics** — motion profiling under real-time constraints on Linux RTOS, with IoT control.

### Selected work

| | |
|---|---|
| **[slm-from-scratch](https://github.com/Jayaragul/slm-from-scratch)** | A 27,846,000-parameter decoder-only transformer trained on TinyStories. Hand-written causal attention, weight-tied embeddings, memory-mapped data pipeline. Trained weights included. |
| **[INFERENCING-LLM-LAMA](https://github.com/Jayaragul/INFERENCING-LLM-LAMA)** | Privacy-first local AI platform with agentic capabilities — web search, RAG and tools. Runs fully offline on Ollama + FastAPI. |
| **[industrial-data-agent](https://github.com/Jayaragul/industrial-data-agent)** | Safety-first Gemini-powered CLI for evidence-backed analysis of industrial orders, machine utilisation and inventory, with sandboxed code execution. |
| **[AGENT-HARNESS](https://github.com/Jayaragul/AGENT-HARNESS)** | Factory AI Copilot — an industrial assistant for inventory checks, machine requirement analysis and risk reports, behind a chat interface. |
| **[health-care-agent](https://github.com/Jayaragul/health-care-agent)** | Healthcare information assistant built on AI-harness principles, with guardrails and a clear split between routing, tools and generation. |
| **[agri-hackathon](https://github.com/Jayaragul/agri-hackathon)** | **Thulir** — an AI farming companion for smallholder farmers. Winner: Best Use of AI for Zero Hunger & Economic Growth, GDG Tech for Good 2026. |
| **[factory-twin](https://github.com/Jayaragul/factory-twin)** | Real-time 3D factory digital twin with AI anomaly detection. React + Three.js front end, FastAPI + SQLAlchemy back end. |
| **[kidney](https://github.com/Jayaragul/kidney)** | Streamlit app predicting kidney-disease risk from clinical parameters such as age, blood pressure and blood sugar. |

---

### How my agents actually work

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./pipeline-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./pipeline-light.svg">
  <img alt="Agent pipeline: query, intent routing, expert selection, tool use, shared memory, response" src="./pipeline-dark.svg">
</picture>

A query gets classified by intent, routed to the expert best suited to it, answered with tools
where needed, and merged back into shared memory so the next turn has context. Not one-shot
prompting.

---

### Writing

<!-- MEDIUM:START -->
- [Why Agentic AI Is the Next Big Shift in Artificial Intelligence](https://medium.com/@jayaragul/why-agentic-ai-is-the-next-big-shift-in-artificial-intelligence-ead0b98adabe) &nbsp;<sub>23 May 2026</sub>
- [From ‘Attention Is All You Need’ to My Own GPT: Training an SLM From Scratch](https://medium.com/@jayaragul/from-attention-is-all-you-need-to-my-own-gpt-training-an-slm-from-scratch-b426ab9ec604) &nbsp;<sub>31 Dec 2025</sub>
- [“Two Days, One Summit, Infinite Lessons: Our Start-up's Takeaways from TNGSS 2025”](https://medium.com/@jayaragul/two-days-one-summit-infinite-lessons-our-start-ups-takeaways-from-tngss-2025-983757508696) &nbsp;<sub>12 Oct 2025</sub>
- [“Why Sitting in Class Why not bunk: Real Skills Every Engineering Student Should Gain”](https://medium.com/@jayaragul/why-sitting-in-class-why-not-bunk-explore-engineering-in-641a5e1bbc8c) &nbsp;<sub>14 Dec 2024</sub>
<!-- MEDIUM:END -->

### Working with

`Python` · `PyTorch` · `SQL` · `Django` · `Flask` · `OpenCV` · `TensorFlow` · `pandas` · `scikit-learn` · `MongoDB` · `LLMs & fine-tuning` · `Agentic AI` · `Google Cloud` · `Linux RTOS` · `Git`

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Jayaragul/Jayaragul/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Jayaragul/Jayaragul/output/snake-light.svg">
  <img alt="Contribution graph rendered as a snake" src="https://raw.githubusercontent.com/Jayaragul/Jayaragul/output/snake-light.svg">
</picture>

---

[Portfolio](https://jayaragul.github.io/MY-PORTFOLIO-WEBSITE/) · [Medium](https://medium.com/@jayaragul) · jayaragul.in@gmail.com
