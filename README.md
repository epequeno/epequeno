## Hi, I'm Estevan

AI engineer focused on **LLM evaluation and agent reliability**: measuring where agents and
small models fail, and building the tooling to catch it. I also build production AWS
systems (Rust, Lambda, Bedrock, CDK) and spent 10+ years as a public-sector and
regulated-industry solutions architect.

### Projects

| Project | What it shows |
|---|---|
| [agent-fail-eval](https://github.com/epequeno/agent-fail-eval) | What context compaction silently drops from coding-agent sessions. 115 real sessions, 213 compaction events; 94.6% of extracted user constraints absent from summaries (heuristic extraction) |
| [toolshift-bench](https://github.com/epequeno/toolshift-bench) | 397-task tool-calling benchmark, 4 new metrics, 8 open models. Models of 3B or fewer pick the right tool ~90% of the time but make a fully correct call only 41–72% |
| [rlm-switch](https://github.com/epequeno/rlm-switch) | Learned router across context strategies: 42% lower cost than always-RLM for a 4-point accuracy drop |
| [grokking-geography](https://github.com/epequeno/grokking-geography) | Which components drive the grokking transition; includes an optimizer-reset confound I caught in my own results |
| [mathmate](https://github.com/epequeno/mathmate) | A desktop AI math tutor built around a research finding (unguarded AI access degrades learning): Tauri + React + Rust, a Socratic hint ladder behind an attempt-first gate, guardrails designed to scaffold rather than substitute |
| [support-triage](https://github.com/epequeno/support-triage) | A support-triage agent with its receipts: policy-grounded SLA commitments, gated state changes a named human approves, measured model routing (forced tiers tie at a 214× cost difference; routed runs 50/50 at $0.30/ten cases), and a one-stack CDK deploy that was deployed once, photographed, and torn down |
| [eapsoftware.dev](https://eapsoftware.dev) | Production LLM pipeline on Amazon Bedrock (Rust, Lambda, EventBridge, DynamoDB, CDK) |

### Stack
`Python` · `Rust` · `PyTorch` · `AWS Bedrock` · `Lambda` · `DynamoDB` · `CDK` · `DSPy`

### Certifications
AWS Certified Generative AI Developer – Professional · AWS Certified Machine Learning – Specialty

[LinkedIn](https://www.linkedin.com/in/estevan-pequeno-95407825) · [Credly](https://www.credly.com/users/estevan-pequeno)
