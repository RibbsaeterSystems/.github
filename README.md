<div align="center">

  <img src="https://raw.githubusercontent.com/RibbsaeterSystems/.github/main/assets/ribbsaeter_systems_hero.png" alt="Ribbsaeter Systems — Builds Serious Systems" width="100%" />

  <br />

  <p align="center">
    <code>ZURICH · AMSTERDAM · EINDHOVEN</code> &nbsp;◆&nbsp;
    <a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems"><b>ZeroSlop™ on GitHub Marketplace</b></a> &nbsp;◆&nbsp;
    <a href="https://ribbsaetersystems.com"><b>ribbsaetersystems.com</b></a> &nbsp;◆&nbsp;
    <a href="https://patrickribbsaeter.com"><b>patrickribbsaeter.com</b></a>
  </p>

  <p align="center">
    <a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems">
      <img src="https://img.shields.io/badge/GitHub_Marketplace-Official_Developer-00F0FF?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="Official GitHub Marketplace Developer" />
    </a>
    &nbsp;
    <a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems">
      <img src="https://img.shields.io/badge/Marketplace_Partner-Ribbsaeter_Systems-10B981?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=0d1117" alt="GitHub Marketplace Partner" />
    </a>
    &nbsp;
    <a href="https://github.com/apps/zeroslop-engine">
      <img src="https://img.shields.io/badge/GitHub_App-ZeroSlop--Engine-8B5CF6?style=for-the-badge&logo=probot&logoColor=white&labelColor=0d1117" alt="GitHub App ZeroSlop-Engine" />
    </a>
  </p>

</div>

---

### Executive Overview

**Ribbsaeter Systems** is an **Official GitHub Marketplace Developer**, specialized developer tooling house, and software invariant laboratory founded by **[Patrick Ribbsaeter](https://patrickribbsaeter.com)**. We engineer deterministic pull request gatekeepers, compiler-grade invariant verifiers, and production developer tools designed to protect enterprise codebases against synthetic bloat and AI-generated regressions.

The marginal cost of software generation has collapsed to near-zero. Autonomous coding agents synthesize hundreds of lines of code in seconds—yet over 80% of AI-generated pull requests introduce unreviewed surface area, cosmetic churn, and unauthorized test deletions to bypass CI. 

Every uninspected line of synthetic diff is an enterprise balance sheet liability. Ribbsaeter Systems builds the mechanical layer that enforces code minimization, protects test suites, and guarantees that only verified, minimal diffs enter production.

---

### The Flagship Product: ZeroSlop™

<div align="center">
  <a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems">
    <img src="https://raw.githubusercontent.com/RibbsaeterSystems/.github/main/assets/zeroslop_architecture_banner_swissred.svg" alt="ZeroSlop™ by Ribbsaeter Systems - Sovereign CI Invariant Airlock" width="100%" />
  </a>

  <p align="center">
    <a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems"><b>ZeroSlop™ Action</b></a> &nbsp;◆&nbsp;
    <a href="https://github.com/apps/zeroslop-engine"><b>1-Click GitHub App</b></a> &nbsp;◆&nbsp;
    <a href="https://ribbsaetersystems.com/zeroslop"><b>Live Simulator</b></a> &nbsp;◆&nbsp;
    <a href="https://ribbsaetersystems.com/zeroslop/security"><b>Zero-Retention Security</b></a>
  </p>
</div>

<br/>

**[ZeroSlop™ by Ribbsaeter Systems](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems)** is an autonomous CI pull request invariant gatekeeper and diff minimization engine. It audits incoming PR diffs against strict architectural bounds before code ever reaches human review or wastes expensive CI runner compute.

#### Why Engineering Teams & CTOs Deploy ZeroSlop:

1. **50%–70% Diff Footprint Reduction**: Enforces strict AST diff-to-scope minimization, stripping phantom refactorings, cosmetic renames, and gratuitous line bloat.
2. **Zero Test Deletion Shield**: Halts pull requests immediately with `exit code 1` if an agent or contributor deletes existing unit tests or relaxes assertions to fake green builds.
3. **12-Shield Deterministic CWE Security Airlock**: Ephemerally inspects diffs for SQLi (`CWE-89`), hardcoded secrets (`CWE-798`), IDOR (`CWE-639`), command injection (`CWE-78`), SSRF (`CWE-918`), and CI workflow Pwn Requests (`CWE-426`).
4. **Zero-Click Blast Radius & Single In-Place PR Card**: Post-processing outputs a concise, self-updating PR status verdict directly in GitHub without third-party dashboard clutter.
5. **Zero Data Retention (Enterprise Sovereign Standard)**: All diff evaluations execute ephemerally in RAM and are purged immediately. No code is stored on disk, and zero proprietary IP is transmitted to external LLM providers.

#### Two 1-Click Deployment Options:
* 🚀 **GitHub App (1-Click Install)**: [Install ZeroSlop Engine App](https://github.com/apps/zeroslop-engine) &mdash; Organization-wide webhook enforcement with single self-updating PR verdict cards.
* ⚙️ **GitHub Action**: [Deploy ZeroSlop Action](https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems) &mdash; Two-line YAML step running inside volatile GitHub Actions runner memory.

---

### Dual Pillars of Operation

```
┌─────────────────────────────────────────────────────────┬─────────────────────────────────────────────────────────┐
│     PILLAR I: AUTONOMOUS DEVELOPER PLATFORMS            │     PILLAR II: SYSTEMS PRACTICE & ADVISORY              │
├─────────────────────────────────────────────────────────┼─────────────────────────────────────────────────────────┤
│ • ZeroSlop™ Engine (GitHub App & Action)                │ • Production Systems Architecture & Code Audits         │
│ • Deterministic AST invariant CI airlock                │ • Memory Footprint & KV Cache Optimization Sprints       │
│ • Mechanical interception of AI slop & test deletions   │ • Principal Systems Architecture Retainer               │
│ • 12-Shield deterministic CWE security gatekeeper       │ • Provenance across compilers, databases, and runtimes  │
└─────────────────────────────────────────────────────────┴─────────────────────────────────────────────────────────┘
```

---

### The Wall of Sovereign Proof (Upstream Engineering Proof Ledger)

ZeroSlop's invariant standards are not theoretical. Our core engineering methods have been battle-tested and merged directly into the most demanding compilers, query engines, runtimes, and databases in modern computing across 4 foundational engineering pillars:

#### ⚡ 1. Frontier AI Inference, GPU Compilers & LLM Runtimes
*KV-cache prefix optimization, GPU kernel interface slots, model tokenizer parity, and high-throughput inference serving.*

| Project | Domain & Stack | Architectural Invariant & Engineering Focus | Upstream Work |
| :--- | :--- | :--- | :---: |
| **Hugging Face Diffusers** | GenAI · Python | InpaintProcessor 3-tuple return contract preservation when mask tensor input is None | **Merged**<br/>[PR #14481](https://github.com/huggingface/diffusers/pull/14481) |
| **SGLang** | LLM Runtime · CUDA | Mid-turn inline system message in-place attachment preserving RadixAttention prefix cache | **Checks Green**<br/>[PR #42533](https://github.com/sgl-project/sglang/pull/42533) |
| **vLLM** | LLM Serving · Python | Warn on unsupported non-text system content blocks in Anthropic Chat API | **Checks Green**<br/>[PR #61721](https://github.com/vllm-project/vllm/pull/61721) |
| **vLLM** | LLM Serving · Python | Empty and non-mapping YAML configuration validation preventing unhandled CLI startup crash | **Checks Green**<br/>[PR #60319](https://github.com/vllm-project/vllm/pull/60319) |
| **OpenAI Triton** | GPU Compiler · C++ | Nanobind static build free-threaded Python PEP 703 GIL module slot declaration | **Checks Green**<br/>[PR #12221](https://github.com/triton-lang/triton/pull/12221) |
| **Meta TorchTune** | LLM Training · Py | Mistral and Gemma end-token generation stopping control and tokenizer parity | **3/3 Green**<br/>[PR #2977](https://github.com/meta-pytorch/torchtune/pull/2977) |
| **Aider** | AI Dev Tool · Python | Enforce strict token budget ceiling during repository map binary search | **Checks Green**<br/>[PR #5854](https://github.com/Aider-AI/aider/pull/5854) |
| **Continue** | AI Dev Tool · TS | Prevent negative prompt budget and silent prompt wipeout on small context models | **Checks Green**<br/>[PR #13379](https://github.com/continuedev/continue/pull/13379) |

<br/>

#### 🏛️ 2. Compilers, Low-Level Systems & MicroVM Infrastructure
*Vector code generation, register liveness preservation, async event-loop timer tracking, and kernel-adjacent microVM runtimes.*

| Project | Domain & Stack | Architectural Invariant & Engineering Focus | Upstream Work |
| :--- | :--- | :--- | :---: |
| **LLVM** | Compiler · C++ | X86 SelectionDAG non-power-of-two vector integer division vectorization and target lowering | **Merged**<br/>[PR #215076](https://github.com/llvm/llvm-project/pull/215076) |
| **Tokio** | Async Runtime · Rust | Current-thread paused time wake tracking and zero-syscall timer queue preservation | **Merged**<br/>[PR #8595](https://github.com/tokio-rs/tokio/pull/8595) |
| **LLVM** | Compiler · C++ | X86 CodeGen preserve XMM register liveness across VZEROUPPER and check register clobbers | **12/12 Green**<br/>[PR #218873](https://github.com/llvm/llvm-project/pull/218873) |
| **AWS Firecracker** | MicroVM · Rust | Resolved clippy infallible destructuring match on TimerFd in optimized release builds | **3/3 Green**<br/>[PR #6262](https://github.com/firecracker-microvm/firecracker/pull/6262) |
| **Bun** | JS Runtime · Zig | Node.js Buffer per-encoding methods receiver type conformance in JavaScriptCore bindings | **2/2 Green**<br/>[PR #44571](https://github.com/oven-sh/bun/pull/44571) |
| **Cloudflare Workers SDK** | Edge Runtime · TS | Raw TCP socket streaming and backpressure handling for rejected WebSocket upgrades | **54/54 Green**<br/>[PR #15205](https://github.com/cloudflare/workers-sdk/pull/15205) |

<br/>

#### 💾 3. High-Performance Data Engines & Distributed OLAP
*Vectorized query execution, partition in-memory ordering, schema nullability conformance, and distributed storage engines.*

| Project | Domain & Stack | Architectural Invariant & Engineering Focus | Upstream Work |
| :--- | :--- | :--- | :---: |
| **Apache Arrow** | Columnar Format · Rust | Correctness fix for Fields::filter_leaves nested traversal on ListView and LargeListView | **Merged**<br/>[PR #11657](https://github.com/apache/arrow-rs/pull/11657) |
| **DuckDB** | Database · C++ | PIVOT IN list zero-argument `row()` expression preservation and null dereference guard | **Merged**<br/>[PR #26443](https://github.com/duckdb/duckdb/pull/26443) |
| **Meta Velox** | Query Engine · C++20 | TopNRowNumber in-memory rank ordering correctness and partition stream execution parity | **Merged**<br/>[PR #18529](https://github.com/facebookincubator/velox/pull/18529) |
| **Apache DataFusion** | Query Engine · Rust | Execution-layer schema conformance across in-memory physical execution and aggregation | **Merged**<br/>[PR #24394](https://github.com/apache/datafusion/pull/24394) |
| **Valkey** | Datastore · C99 | Cluster key-slot resolution and client-side cache validation for arbitrary key commands | **Merged**<br/>[PR #4424](https://github.com/valkey-io/valkey/pull/4424) |
| **ClickHouse** | OLAP Engine · C++20 | Bounds validation on parallel replicas legacy query plan limit enforcement pipeline | **174/176 Green**<br/>[PR #114954](https://github.com/ClickHouse/ClickHouse/pull/114954) |
| **Apache DataFusion** | Query Engine · Rust | PushDownFilter clippy mutable key type allow annotations for logical Expr hash sets | **43/43 Green**<br/>[PR #26189](https://github.com/apache/datafusion/pull/26189) |
| **Apache DataFusion** | Query Engine · Rust | Safe downcast to FixedSizeBinaryArray in CASE literal vectorized lookup evaluation table | **Merged**<br/>[PR #26096](https://github.com/apache/datafusion/pull/26096) |
| **Apache DataFusion** | Query Engine · Rust | Sort-merge semi, anti, and mark join key equality routing via JoinKeyComparator | **42/42 Green**<br/>[PR #26006](https://github.com/apache/datafusion/pull/26006) |
| **Redpanda** | Streaming · C++20 | RPC transport memory semaphore unit retention across queued outbound request entries | **9/9 Green**<br/>[PR #31594](https://github.com/redpanda-data/redpanda/pull/31594) |
| **Supabase Supavisor** | Pooler · Elixir | PostgreSQL query cancellation key synchronization across pooled backend connection reuse | **Checks Green**<br/>[PR #1149](https://github.com/supabase/supavisor/pull/1149) |

<br/>

#### 🤖 4. Autonomous Agent Protocols, Type Systems & Security Governance
*Deterministic approval chains, MCP protocol streaming, type inference hierarchies, and cryptographic consensus.*

| Project | Domain & Stack | Architectural Invariant & Engineering Focus | Upstream Work |
| :--- | :--- | :--- | :---: |
| **Microsoft Pyright** | Type Checker · TS | Inherited asymmetric descriptor detection and type inference across effective MRO hierarchy | **Merged**<br/>[PR #11605](https://github.com/microsoft/pyright/pull/11605) |
| **Microsoft TypeSpec** | API Compiler · TS | Playground state synchronization and deterministic compiler regression suite coverage | **Merged**<br/>[PR #11660](https://github.com/microsoft/typespec/pull/11660) |
| **Microsoft Agent Governance** | Agent Safety · Python | Fail-closed approval-chain invariant enforcement for zero-required-stage configurations | **Merged**<br/>[PR #3448](https://github.com/microsoft/agent-governance-toolkit/pull/3448) |
| **Microsoft Agent Governance** | Agent Safety · Python | Policy fixture schema validation rejecting test definitions missing explicit expectations | **Merged**<br/>[PR #3442](https://github.com/microsoft/agent-governance-toolkit/pull/3442) |
| **eBay NuRaft** | Consensus · C++17 | Rejection of concurrent snapshot sync requests during asynchronous finalization race window | **Merged**<br/>[PR #663](https://github.com/eBay/NuRaft/pull/663) |
| **Bushido Han** | Agent Tooling · Rust | Windows project-path normalization compatibility with Claude Code workspace slug rules | **Merged**<br/>[PR #105](https://github.com/TheBushidoCollective/han/pull/105) |
| **Anthropic MCP SDK** | Agent Protocol · TS | Stream resumption support for SSE event identifiers containing underscore delimiter tokens | **14/14 Green**<br/>[PR #2567](https://github.com/modelcontextprotocol/typescript-sdk/pull/2567) |
| **Ledger Ragger** | Secure Element · Py | Hardware wallet firmware project discovery across linked git worktrees and submodules | **7/7 Green**<br/>[PR #291](https://github.com/LedgerHQ/ragger/pull/291) |
| **Ethereum go-ethereum** | Execution · Go | Bound leveldb/pebble database batch memory size during filtermaps log index rollback | **Checks Green**<br/>[PR #35586](https://github.com/ethereum/go-ethereum/pull/35586) |
| **Paradigm Reth** | Execution · Rust | Transaction pool live iterator candidate demotion when earlier transactions are reinserted | **Mergeable**<br/>[PR #27707](https://github.com/paradigmxyz/reth/pull/27707) |
| **Web3.py** | Ethereum SDK · Py | Async socket teardown lifecycle synchronization and deterministic future test harness | **Tests Green**<br/>[PR #3872](https://github.com/ApeWorX/web3.py/pull/3872) |
| **Vercel Next.js** | Web Framework · TS | Segment-cache client navigation recovery with full-page fallback guard on stale prefetches | **3/3 Green**<br/>[PR #97815](https://github.com/vercel/next.js/pull/97815) |

> Independent upstream engineering. Contributions do not imply employment, partnership, endorsement, or client relationships with the organizations listed above.

---

### The Sovereign Engineering Standard

1. **Zero-Defect Rule**: 100% of contributor-controlled checks (tests, types, linters, invariants) must be validated green locally prior to deployment.
2. **Minimal Durable Diffs**: The objective is never maximum code output. It is the smallest correct change that fits the system without degrading invariants.
3. **Quiet Luxury & Sovereign Quality**: Software that speaks through mathematical correctness, compiler validation receipts, and zero operational drama.

---

<div align="center">

  <a href="https://github.com/marketplace/actions/zeroslop-by-ribbsaeter-systems">
    <img src="https://raw.githubusercontent.com/RibbsaeterSystems/.github/main/assets/deploy_zeroslop_banner_animated.svg" alt="Deploy ZeroSlop™ by Ribbsaeter Systems on GitHub Marketplace" width="100%" />
  </a>

</div>
