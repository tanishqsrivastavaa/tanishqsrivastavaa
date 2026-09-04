# hi, i'm tanishq.

i build AI systems and like understanding how they work.

some things i've built:

- [tribeAI](https://github.com/tanishqsrivastavaa/tribeAI) — a minimal agent harness in python. explicit loop, append-only JSONL sessions, context compaction at 60% of the model's budget, and tools confined to a workspace root behind an approval gate.
- [EvalWatch](https://evalwatch.tanishq.works) — LLM observability. apps post traces, celery workers persist them off the request path, and a judge model scores each one for relevance and groundedness.
- [TalkToYourData](https://github.com/tanishqsrivastavaa/TalkToYourData) — voice-native agentic RAG. upload PDFs and talk to them: whisper listens, GPT-4o-mini reasons over pgvector retrieval, cartesia answers back over LiveKit.
- [UNaFIED](https://github.com/tanishqsrivastavaa/UNaFIED) — realtime chat where one agent follows the conversation and another runs pgvector search to surface relevant things mid-sentence.
- [petique-app](https://github.com/tanishqsrivastavaa/petique-app) — vet appointment platform. FastAPI and SQLModel behind React 19, with availability modelled as weekly working hours plus time-off blocks.

older stuff:

- [cliipu](https://github.com/tanishqsrivastavaa/cliipu-tui) — clipboard manager for wayland. a background daemon watches wl-paste, history goes to SQLite, a Textual TUI browses it.
- [MemoryWeave](https://github.com/tanishqsrivastavaa/MemoryWeave-v2) — real-time object detections woven into narrative timelines. 1st of 200+ teams at hacksrm'25.

currently:

- AI inference
- LLM internals
- backend systems
- developer tooling
- research
