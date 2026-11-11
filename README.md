# From Threat to Safeguard: A Survey of Agentic Safety Research Through the Lens of Threat Modeling

**Satyapriya Krishna**

📄 **[Read the paper (PDF)](From_Threat_to_Safeguard.pdf)**

The arXiv version is forthcoming; this repository hosts the paper in the meantime.

## Abstract

Large language model (LLM) agents now act with delegated authority: they read mail, make purchases, run code in real repositories and negotiate with other agents. Research on their safety has grown quickly and is largely organized around benchmarks. A benchmark measures how often an agent fails on a set of tasks, but it leaves open other questions practitioners face when they deploy an agent. Given what the agent can access and do, there are several ways it could cause harm: through instructions an attacker hides in the content it reads, through a user who misuses it, through its own mistakes or goals, through its interactions with other agents, or through a gap in the sandbox and permissions around it. Has anyone measured how often each of these harms occurs in a deployment like theirs? And does a safeguard exist that has held up when someone other than its designers tried to break it? To show how far current research answers these questions, we survey agentic safety research through the lens of threat modeling. The survey makes three contributions: (1) a map that groups the ways an agent can cause harm into six families and 24 threat vectors and places 1036 works under the vectors and lifecycle stages (identification, evaluation or mitigation) they address; (2) a status report that traces each vector from identification to mitigation; and (3) for each vector, the weakest link in this chain and the most common open problems. The status report finds that 20 of the 24 vectors have an independent evaluation of a mitigation. In only 12 of them did a mitigation pass that evaluation. Independent adaptive attacks, drawn from 26 studies, degraded the targeted safeguards in 8 of the 13 vectors where we found them. In the documents we collected, sandbox and permission failures and failures without an attacker make up a larger share of incident reports than of evaluation studies (20.8% against 4.6% and 37.7% against 22.7%). Across the corpus, authors most often call for tests against stronger and adaptive attackers.

## Citation

```bibtex
@misc{krishna2026threat,
  title  = {From Threat to Safeguard: A Survey of Agentic Safety Research Through the Lens of Threat Modeling},
  author = {Krishna, Satyapriya},
  year   = {2026},
  note   = {Working draft}
}
```

Comments and pointers to work we missed are welcome: spkrishna@alumni.harvard.edu
