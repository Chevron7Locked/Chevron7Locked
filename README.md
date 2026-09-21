# Kevin O'Neill

I build AI agent systems and run the infrastructure underneath them. 6 machines, models I host myself. Professional developer since 2016, leading development teams since 2020.

### What I build

**[Kima Hub](https://github.com/Chevron7Locked/kima-hub)** · 1,280 stars
Self-hosted music server. Every track carries a 514-dimension vector fusing CLAP audio embeddings with valence and arousal. Each listener is the average of what they've played. Discovery is cosine distance over a pgvector HNSW index. Across 18,255 tagged tracks, nearest neighbors share a mood 24% of the time against 7% for random pairs.

**ADAgent** *(private)*
Detects across the WCAG 2.2 A/AA surface with 36 engines and repairs 25 violation classes without a human. Traces each violation back to whatever produced it: a template, a stylesheet, PHP, a row in the database. Then writes the fix. Mixed agentic and deterministic by design: the agent loop finds the source and picks the route, the fixers it dispatches to are deterministic scripts. The model handles the judgment calls, alt text and documenting what it refused to touch. 5 checks run before anything merges.

**Research corpus** *(private)*
Semantic search service in production. Answers carry cited passages. 1,735 source documents across roughly 17 collections, every PDF verified and checksummed. Serves five agent seats. Python, PostgreSQL, pgvector.

**Silta** *(private, deployed)* · `silta-hub`
App-agnostic social backbone in Go. The core deals only in generic concepts: activities, presence, profiles, chat. App semantics live in connectors. One static binary over PostgreSQL and Redis. Instances register with each other over Ed25519.

**[lm-chat](https://github.com/Chevron7Locked/lm-chat)** · Web front end for LM Studio. Browser and phone access to models you host, MCP tools, and a memory that distills your context out of past conversations and carries it across model swaps.

### Open source

Two pull requests merged into [openclaw](https://github.com/openclaw/openclaw), 390k stars: auto-failover overrides cleared so the primary model retries after a fallback, and gateway installs no longer dropping `.env` variables. One merged into [freelingo](https://github.com/artcc/freelingo).

Open pull requests against [Hermes Agent](https://github.com/NousResearch/hermes-agent) and [Hermes WebUI](https://github.com/nesquena/hermes-webui): CLI root resolution, supervised-process restarts, idempotent run-journal recovery, per-chat reasoning effort.

### Working with

`TypeScript` `Python` `Go` `SvelteKit` `PostgreSQL + pgvector` `Redis` `Docker` `vLLM` `ONNX Runtime` `MCP`

### Audio before software

Interned with Joey Sturgis at Foundation in Michigan for Crown the Empire's *The Fallout*, tracked with my Lauten Audio Oceanus. Before that, SoundScape Studios in Chicago with Mike Kolar. Playing shows, short tours, recording myself and a lot of local artists.

Elgin Community College, C++ coursework through most of the second year. Self-taught after that. First site was sassykatrecords.com in 2012, for my own studio.

---

kevin@chevron7.io · [linkedin.com/in/kevinallen3](https://linkedin.com/in/kevinallen3)
