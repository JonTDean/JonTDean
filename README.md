<!-- About -->
<img src="/about.svg" alt="About Me">

<p align="justify">

I am a machine learning engineer, computational biologist, and systems designer working where **clinical informatics, cybernetics, and information theory** meet. My day job is building **high-stakes data and ML systems** for oncology and real-world evidence; my longer-horizon work is about treating those systems as **goal-directed, feedback-rich processes** rather than mere data plumbing.

Formally, my background combines **bioinformatics & computational biology**, **computer science**, and **data infrastructure engineering**. Conceptually, I draw a line from early **cybernetics** (control and communication in organisms and machines) through **information theory** (information as the resolution of uncertainty) to modern **AI and multi-scale cognition**. My focus is making that lineage concrete in code: ontologies become vectors; feedback loops become APIs; evaluation becomes a first-class artifact.

</p>

---

<!-- Fingerprint -->
<img src="/fingerprint.svg" alt="Fingerprint">

### Research & Practice Fingerprint

- **Cybernetics & information flow**
  - Model clinical platforms as **feedback systems**: sensors (EHR, labs, genomics), controllers (mapping engines, policies), actuators (dashboards, decision support).  
  - Treat pipelines as **communication channels** with noise, capacity, and distortion; design for graceful degradation instead of silent failure.

- **Vectorized ontologies & representation geometry**
  - Embed NCIt, SNOMED CT, UMLS, RxNorm, FHIR value sets, and OBO ontologies into vector spaces; analyze **manifold structure, capacity, and community detection** (Leiden/Louvain).  
  - Build **mapping engines** that combine approximate nearest neighbors, lexical features, and domain constraints to align FHIR resources and procedural codes to ontology terms.

- **Clinical data systems & governance**
  - Architect **federated data meshes**: per-site marts and warehouses backed by relational + vector stores, coordinated by a mesh hub with policy, lineage, and evaluation.  
  - Emphasize **auditability and epistemic humility**: every mapping, score, and model decision should be traceable, inspectable, and falsifiable.

- **Working style**
  - Kanban-driven development, small reviewable PRs, and CI that enforces formatting, linting, tests, and documentation.  
  - Preference for **strong types and explicit invariants** (Rust / typed schemas) in pipelines that must be correct for years, not just demos.

---

<!-- Github -->
<img src="/github.svg" alt="Github">

### What I Use GitHub For

- **Data-First Procedural Semantics (DFPS) / clinical platform work**
  - Multi-crate Rust workspace for:
    - FHIR bundle ingestion, validation, and normalization.  
    - Ontology-aware mapping of service requests, procedures, and observations to NCIt and related vocabularies via vector backends (FAISS / pgvector / similar).  
    - Mesh-style orchestration across local datamarts, analytics marts, and shared governance layers.

- **Mapping evaluation & information-theoretic probing**
  - CLIs to build, query, and introspect vector indexes; tools to compare **lexical vs. embedding-based vs. hybrid** matching strategies.  
  - Analyze error modes as **information-processing failures**: ambiguous codes, underspecified contexts, brittle embeddings, and graph pathologies.

- **Frontends & inspection tools**
  - Next.js + Tailwind + ShadCN UIs for:
    - Inspecting mapping neighborhoods (top-k candidates, confidence scores, lexical/semantic evidence).  
    - Visualizing ontology graphs, local manifolds, and evaluation metrics in ways that clinicians and data stewards can actually reason about.

---

<!-- Code -->
<img src="/code.svg" alt="Programming Data">

### Engineering Stack & Practices

- **Languages & ecosystems**
  - **Rust** for domain models, ingestion pipelines, mapping engines, governance / mesh services.  
  - **Python** for experimentation, data analysis, evaluation harnesses, and research prototypes.  
  - **TypeScript / React / Next.js** for visual analytics, operator consoles, and developer tooling.

- **Data & infra**
  - **PostgreSQL + SQLx** for relational cores; **dimensional datamarts / warehouses** for downstream analytics.  
  - **Vector stores** (FAISS, pgvector-style backends, ANN indices) as an explicit **ontology layer**, not an afterthought.  
  - Containers and IaC (Docker, Terraform-style tooling) with GitHub Actions CI that runs `fmt`, `lint`, `test`, and doc checks.

- **Design principles**
  - Domain-driven structure: `domain` (semantics), `platform` (infrastructure), `app` (interfaces), each with narrow, testable contracts.  
  - Extensive CLI entry points (e.g., `build_vector_index`, `map_bundles`, `map_codes`, `eval_mapping`, `load_datamart`, `validate_fhir`) so experiments and pipelines are scripted, versioned, and repeatable.  
  - Treat metrics, logs, and traces as **feedback signals** for a cybernetic system rather than mere observability garnish.

---

<!-- Languages -->
<img src="/languages.svg" alt="Language Data">

### Technical & Natural Languages

- **Programming**
  - Primary: Rust, Python, TypeScript  
  - Also: SQL, Bash, occasional JVM/web tooling when interfacing with legacy systems  
  - Tooling: cargo, poetry/pip, Node/Bun, modern linters/formatters, GitHub Actions / similar CI.

- **Communication**
  - Write **design docs, evaluation reports, and governance notes** that tie together code, data, and outcomes.  
  - Strong bias toward:
    - Declaring assumptions and failure modes up front.  
    - Making epistemic status explicit (“measured”, “estimated”, “hypothesized”).  
    - Translating between engineers, clinicians, data stewards, and leadership.

---

### Guiding perspectives (selected quotes)

> “Information is information, not matter or energy.”  
> — Norbert Wiener  

> “Information is the resolution of uncertainty.”  
> — Claude Shannon  

> “Artificial intelligence is the science and engineering of making intelligent machines, especially intelligent computer programs.”  
> — John McCarthy  

> “Novel beings, novel goals.”  
> — Michael Levin  

<sub>
If you are thinking in the same space—**cybernetics-inspired clinical systems, information-theoretic views of pipelines, vectorized ontologies, and multi-scale cognition**—I’m always open to conversations, issues, or collaborative experiments.
</sub>
