<h1>Hi, I'm Artem <img src="./assets/waving-banana.gif"></h1>

[artemlegotin.com](https://artemlegotin.com/) • [LinkedIn](https://www.linkedin.com/in/artemlegotin/) • [Telegram](https://t.me/artemlegotin) • [email](mailto:artem@artemlegotin.com)

I’ve been a software engineer since 2013, building AI products since 2020.

## What I do

I focus on agentic LLM systems, generative AI, and recommender systems.

Currently, I’m Head of AI at [exactly.ai](https://exactly.ai/).

Previously I co-founded [neural.love](https://neural.love) and [verstka.io](https://verstka.io/en).

## R&D

- [FamilyTiles](https://github.com/arlegotin/FamilyTiles): lossless weight compression for related language models, saving 20% storage on the tested pair; includes CPU and Metal decoders.
- [Adaptive tree-neurons](https://github.com/arlegotin/adaptive-tree-neurons): grows neural networks with trainable branches inside selected neurons, preserving existing predictions when capacity is added and testing where growth helps.
- [Counterexample-guided operator coalescing](https://github.com/arlegotin/counterexample-guided-operator-coalescing): tests LLM weight sharing across layers to reduce checkpoint size, using low-rank corrections and difficult inputs to choose which layers to merge.
- [FAM-Jet](https://github.com/arlegotin/FAM-Jet): compresses event streams for later time-window queries, testing whether retaining event age improves answers within the same storage budget.
- [Reasoning allocation](https://github.com/arlegotin/reasoning-allocation): tests a learned scheduler for the SCIP optimization solver, choosing search branches and time budgets while counting scheduling overhead against the deadline.
- [AffineFlow](https://github.com/arlegotin/physical-time-consistency): combines learned robot dynamics with actuator physics to predict motion at different timesteps for planning; evaluated on a simulated arm.
- [Outcome-aware context allocation](https://github.com/arlegotin/outcome-aware-context-allocation): tests context budgets for question answering. An evidence-first prompt raised correct answers with exact citations from 27 to 103 on 512 benchmark questions.
- [Customer Pilot Evidence Pack](https://github.com/arlegotin/customer-pilot-evidence-pack): turns search evaluations into offline reports that keep failed requests visible and block provider comparisons when the evidence is incomplete.
- [ExactKV](https://github.com/arlegotin/ExactKV): a lossless codec for LLM attention caches, showing why reconstruction memory erased the tested storage saving.
- [Dependency-aware verification](https://github.com/arlegotin/DAV): tests how coding agents should choose between tests, reviews and documentation checks without treating repeated evidence as independent confirmation.
- [Relational Belief Compilation](https://github.com/arlegotin/RBC): a decision engine that preserves relationships between uncertain facts, acts when all retained interpretations agree, and shows conflicting cases when they don’t.

## Agentic coding tools

- [Pythurion](https://github.com/arlegotin/pythurion): an agent skill for writing small, readable Python changes, with focused checks for correctness and performance.
- [minesweeper](https://github.com/arlegotin/minesweeper): an agent skill that checks untrusted repository text for prompt injection before treating it as instructions.
- [agent-badge](https://github.com/arlegotin/agent-badge): adds a README badge showing recorded AI coding tokens or estimated cost, with usage data stored in the repository.

## Chess is my lifelong love

- [move-merit](https://github.com/arlegotin/move-merit): uses engine analysis and a model of likely moves to explore a chess move’s quality, alternatives and difficulty.
- [chess-gaze](https://github.com/arlegotin/chess-gaze): estimates where chess streamers look from video and visualizes the results in a local 3D viewer.
- [ChessML](https://github.com/arlegotin/chessml): reads chess positions from images using board detection and piece recognition; includes pretrained models and tools for building datasets.
