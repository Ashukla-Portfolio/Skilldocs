# Skill Modes & Outputs Reference

A generated reference table of the **workflow steps (modes)** and **outputs** declared by every `SKILL.md` file in this repository.

## What the columns mean

- **Skill** — the skill folder / `name:` from the SKILL.md frontmatter.
- **Workflow steps (modes)** — the ordered operational phases/steps the skill runs through, extracted from its `Instructions` / `Workflow` / `Phases` (or equivalent) section. Steps are shown in order joined by `→`. `—` means the skill declares no explicit workflow (e.g. reference / knowledge-only skills).
- **Outputs** — what the skill produces, extracted from its `Output Artifact` / `Output Format` / `Deliverable` (or equivalent) section, or inline `Output:` lines. `—` means no explicit output section is declared.

## Coverage

- Total SKILL.md files: **672**
- With explicit workflow steps (modes): **442**
- With explicit outputs: **93**

## Contents

- [Claude Plugin Marketplace](#claude-plugin-marketplace) (217 skills)
- [Claude Skills](#claude-skills) (454 skills)
- [Power BI Analyst Skill](#power-bi-analyst-skill) (1 skills)

## Claude Plugin Marketplace

_217 skills._

### adf-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `adf-master` | — | — |
| `adf-ml-analytics` | — | — |
| `adf-validation-rules` | — | — |
| `databricks-2025` | — | — |
| `fabric-onelake-2025` | — | — |
| `windows-git-bash-compatibility` | — | — |

### ado-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `ado-pipeline-best-practices` | — | — |
| `ado-windows-git-bash-compatibility` | — | — |
| `defender-for-devops` | — | — |
| `sprint-254-features` | — | — |

### azure-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `aks-automatic-2025` | — | — |
| `azure-ml-foundry-workspace` | — | — |
| `azure-openai-2025` | — | — |
| `azure-well-architected-framework` | — | — |
| `container-apps-gpu-2025` | — | — |
| `deployment-stacks-2025` | — | — |

### azure-to-docker-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `azure-emulators-2025` | — | — |
| `compose-patterns-2025` | — | — |
| `docker-watch-mode-2025` | — | — |

### bash-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `advanced-array-patterns` | — | — |
| `bash-53-features` | — | — |
| `bash-master` | — | — |
| `debugging-troubleshooting-2025` | — | — |
| `modern-automation-patterns` | — | — |
| `parallel-processing-patterns` | — | — |
| `process-substitution-fifos` | — | — |
| `security-first-2025` | — | — |
| `shellcheck-cicd-2025` | — | — |
| `string-manipulation-mastery` | — | — |

### cloudflare-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `cloudflare-knowledge` | Scaffold → Pick a storage primitive → Add bindings to wrangler.jsonc → Implement handlers → Develop locally → Deploy | — |

### context-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `context-master` | STOP → PLAN → ANNOUNCE → CREATE → VERIFY | — |

### doc-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `adr-backfill` | Phase 1 — Eligibility and evidence → Phase 2 — Historical context reconstruction (best effort) → Phase 3 — Draft with honesty clause (MANDATORY) → Phase 4 — Save | — |
| `adr-critique` | Phase 1 — Read → Phase 2 — Line-by-line flagging → Phase 3 — Missing-why check → Phase 4 — Consistency check → Phase 5 — LikeC4 drift check → Phase 6 — Apply approved changes | Never bulk-edit. Per-line approval is the discipline that keeps the audit useful.; Never edit an Accepted ADR's body. Allowed edits to an Accepted ADR: typo fixes, graph-compatible header fixes, metadata-only relationship-link fixes explicitly permitted by the project's governance, adding a human-readable superseded by note in the header, or adding a dated "Amendments" note at the bottom under an explicit heading. Anything else is a new ADR.; Surface, don't decide. Tensions, drift, and missing-why are flagged; the architect decides how to resolve.; Report at the end. After applying changes, emit a one-line summary: "Audited NNNN-title.md. <N> flags raised, <M> applied. <K> open items: <list>." |
| `adr-discovery` | 1. Scan, don't summarize → 2. Confirm domain → 3. Confirm components one at a time → 4. Confirm relationships with human-written descriptions → 5. Confirm existing ADRs → 6. Multi-repo + ecosystem probe → 7. Checklist gate → 8. C4 handoff (optional) → 9. Handoff to drafting | — |
| `adr-drafting` | Phase 1 — Understand → Phase 2 — Context → Phase 3 — Options → Phase 4 — Decide → Phase 5 — Draft → Phase 6 — Self-Critique → Phase 7 — Save | — |
| `c4-model` | Phase 1 — Intake → Phase 2 — Locate or scaffold → Phase 3 — Generate DSL → Phase 4 — Canonical-C4 lint → Phase 5 — Show diff, not apply → Phase 6 — Validate syntax → Phase 7 — Render guidance → Phase 8 — Drift check | — |
| `doc-diagnostic` | — | — |
| `markdown-style` | Pass 1 — Syntax (must-fix) → Pass 2 — Style (should-fix) → Apply approved findings | — |
| `repo-health` | Inventory what already exists (README*, LICENSE*, CONTRIBUTING*, → For each cornerstone, run the four-question diagnostic → Recommend create / merge / leave-alone, one file at a time → For files that should be created, load the matching reference; produce → License selection is routed, not made → Same inventory → For each cornerstone present, compare to the canon and flag drift / mi → For each cornerstone absent, ask whether the four-question diagnostic → Produce a numbered KEEP / REWRITE / CREATE / DELETE list | — |

### docker-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `docker-2025-features` | — | — |
| `docker-best-practices` | — | — |
| `docker-git-bash-guide` | — | — |
| `docker-platform-guide` | — | — |
| `docker-security-guide` | — | — |

### dotnet-microservices-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `microsoft-guide` | — | — |

### fal-ai-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `fal-api-reference` | — | — |
| `fal-audio` | Transcribe and Translate Pipeline → Voice Cloning Pipeline → Subtitle Generation → Audio Book Generation | — |
| `fal-image-to-image` | Complete Product Photo Pipeline → Face Restoration Pipeline → Style Transfer with Structure | — |
| `fal-image-to-video` | Portrait Animation Pipeline → Product Showcase → Nature Scene → Fast Preview Workflow | — |
| `fal-model-guide` | — | — |
| `fal-optimization` | — | — |
| `fal-serverless-guide` | — | — |
| `fal-text-to-image` | — | — |
| `fal-text-to-video` | — | — |
| `fal-video-to-video` | Complete Video Enhancement Pipeline → Style Transfer Workflow → Batch Video Processing | — |

### ffmpeg-core

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `ffmpeg-audio-processing` | — | — |
| `ffmpeg-captions-subtitles` | — | — |
| `ffmpeg-command-syntax` | — | — |
| `ffmpeg-deinterlacing-telecine` | — | — |
| `ffmpeg-filter-complex-patterns` | — | — |
| `ffmpeg-fundamentals-2025` | Verify your FFmpeg version with ffmpeg -version → Probe the input with ffprobe to inspect codecs, container, resolutio → Decide whether to remux (-c copy) or transcode (specify enco → Pick encoders and quality settings (see Codec Reference below) → Add filters as needed (see `references/filter-essentials → Verify the output | — |
| `ffmpeg-hardware-acceleration` | Detect what you have → Pick a backend → Build a full-GPU pipeline → Tune quality → Verify | — |
| `ffmpeg-noise-reduction` | — | — |
| `ffmpeg-stabilization-360` | 360/VR Video Processing | — |
| `ffmpeg-video-analysis` | — | — |

### ffmpeg-effects

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `ffmpeg-animation-timing-reference` | Identify the context → Pick a target duration → Snap to frame boundaries → Choose an easing curve → Validate against perception thresholds and sync tolerances → Copy the matching pattern | — |
| `ffmpeg-color-grading-chromakey` | — | — |
| `ffmpeg-glitch-distortion-effects` | — | — |
| `ffmpeg-karaoke-animated-text` | Choose ASS or drawtext → Verify timing units → Probe input when needed → Set output encoding explicitly → Use short test renders → Check readability | — |
| `ffmpeg-kinetic-captions` | — | — |
| `ffmpeg-shapes-graphics` | — | — |
| `ffmpeg-transitions-effects` | — | — |
| `ffmpeg-waveforms-visualization` | — | — |

### ffmpeg-platforms

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `ffmpeg-cicd-runners` | — | — |
| `ffmpeg-cloudflare-containers` | — | — |
| `ffmpeg-docker-containers` | — | — |
| `ffmpeg-modal-containers` | — | — |
| `ffmpeg-streaming` | — | — |
| `ffmpeg-webassembly-workers` | — | — |

### ffmpeg-python

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `ffmpeg-opencv-integration` | Probe input dimensions, fps, duration, and audio streams → Pick the I/O library based on the selection table → Lock pixel format at boundaries (bgr24 for OpenCV pipes; yuv420p f → Process frames in generators/batches; avoid loading full videos unless → Preserve or re-encode audio explicitly → Verify output duration, fps, resolution, codec, and A/V sync | — |
| `ffmpeg-pyav-integration` | Install av from wheels unless you explicitly need a custom FFmpeg bu → Check PyAV and FFmpeg library compatibility before relying on new FFmp → Open containers with a context manager or try/finally close → Select streams explicitly; decode only what you need → Convert frame pixel/sample formats intentionally → For encoding, set codec, dimensions, pixel format, rate, and options e → Disable verbose logging in threaded applications and prefer file paths | — |
| `ffmpeg-python-integration-reference` | Probe the input or metadata source so you know width, height, fps, dur → Choose the integration layer → Normalize color and time units at the Python boundary → Validate parameters and ranges before building a command → Map audio/subtitle streams intentionally → Run on a short sample first; capture stderr for actionable FFmpeg erro | — |

### ffmpeg-social-video

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `viral-video-animated-captions` | Generate transcript with word-level timestamps using Whisper or anothe → Convert word timings into ASS events and styles → Use ASS timing units correctly → Burn ASS into the video with FFmpeg → Verify readability, safe-zone placement, audio sync, and final platfor | — |
| `viral-video-hook-templates` | Generate Multiple Hook Variants | — |
| `viral-video-platform-specs` | Verify ffmpeg -version; prefer current stable builds for security an → Identify target platform(s) and whether the video is native-app upload → Normalize to vertical 9 → Use H → Apply platform loudness targets → Keep -pix_fmt yuv420p and -movflags +faststart for compatibility → Verify output with ffprobe before upload | — |

### git-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `git-2-49-features` | Example 1: Ultra-Efficient Monorepo Clone | — |
| `git-2025-features` | — | — |
| `git-master` | — | — |
| `git-security-2025` | — | — |
| `github-actions-2025` | — | — |
| `github-ai-features-2025` | Daily Workflow | — |

### kaggle-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `competition-workflows` | — | — |
| `datasets-models-sources` | — | — |
| `kaggle-environment` | — | — |
| `kernel-metadata` | — | — |
| `notebook-lifecycle` | Initialize or inspect the local folder → Validate `kernel-metadata → Confirm source file referenced by code_file exists and matches `kern → Choose a conservative timeout and accelerator → Push with kaggle kernels push -p <folder> and optional -t or `--ac → Poll kaggle kernels status <owner/slug> until complete or failed → Use logs, files, and output to diagnose or retrieve artifacts | — |

### ml-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `ml-azureml-adf-automation` | — | — |
| `ml-cloud-deployment` | — | — |
| `ml-data-pipeline` | 1. Initialize and Add Storage → 2. Track a New Dataset Version | — |
| `ml-evaluation` | — | — |
| `ml-fine-tuning` | — | — |
| `ml-hyperparameter-tuning` | — | — |
| `ml-inference-optimization` | Establish a baseline with realistic data, preprocessing, postprocessin → Profile bottlenecks → Apply the least risky optimization first → Revalidate accuracy, calibration, fairness slices, robustness, and num → Measure p50, p95, p99 latency, throughput, memory, cold start, error r | — |
| `ml-mlops` | — | — |
| `ml-training` | — | — |

### modal-compute

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `modal-compute-knowledge` | — | — |

### modal-sandboxes

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `modal-sandboxes-knowledge` | — | — |

### modal-storage

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `modal-storage-knowledge` | Identify whether the workload needs filesystem semantics, key-value st → Mount the storage primitive explicitly on every function/class that ne → For Volumes, commit after writes and reload/read carefully across conc → Keep credentials in Modal Secrets and scope them to the functions that → Validate with a small read/write/delete test before scaling parallel j | — |

### modal-web-scheduling

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `modal-web-scheduling-knowledge` | — | — |

### nextjs-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `nextjs-app-router` | — | — |
| `nextjs-authentication` | — | — |
| `nextjs-caching` | — | — |
| `nextjs-data-fetching` | — | — |
| `nextjs-deployment` | — | 'standalone',; 'export', |
| `nextjs-middleware` | — | — |
| `nextjs-modal-integration` | — | — |
| `nextjs-routing-advanced` | — | — |
| `nextjs-server-actions` | — | — |

### plugin-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `advanced-features-2025` | Maintainer creates ` → Team members clone repo → Trust folder when prompted → Plugins install automatically | — |
| `agent-development` | — | [What to include in responses]; `; Agent descriptions should be concise and effective:; \| Element \| Guideline \|; \|---------\|-----------\|; \| Intro text \| 1-2 sentences on when to trigger \|; \| Example blocks \| 3-7 blocks covering diverse scenarios \|; \| Total description \| Should fit naturally — focus on quality trigger examples over length \| |
| `hook-development` | — | Standard (all hooks):; `json; {; "continue": true,; "suppressOutput": false,; "systemMessage": "Message for Claude"; }; `; PreToolUse decisions:; "hookSpecificOutput": {; "permissionDecision": "allow\|deny\|ask",; "updatedInput": { "field": "modified_value" }; Stop/SubagentStop decisions:; "decision": "approve\|block",; "reason": "Explanation" |
| `plugin-master` | — | — |
| `skill-development` | — | — |
| `triggering-reliability` | — | — |

### powerbi-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `dax-mastery` | — | — |
| `deployment-admin` | — | — |
| `fabric-integration` | — | — |
| `performance-optimization` | — | — |
| `power-query-m` | — | — |
| `powerbi-core` | — | — |
| `programmatic-development` | Pick the source format → Edit programmatically → Validate locally → Parameterize → Deploy → Diff and promote | — |
| `rest-api-automation` | — | — |
| `tmdl-mastery` | — | — |
| `validation-testing` | — | — |

### powershell-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `powershell-2025-changes` | — | — |
| `powershell-7.5-features` | — | — |
| `powershell-master` | Identify scope → Check version & modules → Load the relevant reference(s) → Apply the pre-flight checklist → Validate | — |
| `powershell-security` | — | — |
| `powershell-shell-detection` | Shell-Aware Script Design | — |

### python-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `python-asyncio` | — | — |
| `python-cloudflare` | — | — |
| `python-fastapi` | — | — |
| `python-ffmpeg` | Choose the integration layer first → Probe inputs before processing so codec, duration, resolution, FPS, au → Preserve audio explicitly whenever a video filter is applied; filtered → Select the output codec and acceleration path based on compatibility, → Use overwrite/error-handling patterns consistently → For large media, stream frames or use temp files instead of reading al | — |
| `python-fundamentals-313` | — | — |
| `python-github-actions` | Setup with uv → Dependency Caching with uv | — |
| `python-gotchas` | — | — |
| `python-modal` | — | — |
| `python-opencv` | — | — |
| `python-package-management` | — | — |
| `python-testing` | — | — |
| `python-type-hints` | — | — |
| `python-video-pipeline` | Start by selecting the pipeline architecture → Normalize color and shape conventions at every library boundary → Probe media metadata before processing so FPS, resolution, frame count → Process long videos as streams, batches, or chunks; avoid accumulating → Re-mux or preserve audio after frame-level processing, since OpenCV-on → On Modal or GPU infrastructure, tune batch size, pixel format, decode/ | — |

### react-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `react-forms` | Choose the form model → Define validation near the data contract; prefer schema validation suc → Wire accessibility from the start with labels, aria-invalid, `aria-d → For dynamic fields, use stable field IDs from useFieldArray and pres → For file uploads, validate type/size, generate previews only when appr → For multi-step forms, validate only the current step before advancing | — |
| `react-fundamentals-19` | — | — |
| `react-hooks-complete` | — | — |
| `react-patterns` | — | — |
| `react-performance` | Measure first with React DevTools Profiler, Web Vitals, browser perfor → Identify the bottleneck class → Apply the smallest targeted fix → For media-heavy UIs, protect video element identity, avoid remounting, → Re-measure after each change and keep only optimizations that improve | — |
| `react-state-management` | — | — |
| `react-testing` | Set up the runner and jsdom environment first, then centralize `@testi → Write tests from the user perspective using role, label, text, placeho → Use `userEvent → Mock at module or network boundaries, not internal component state, an → Create provider-aware render utilities for context, routers, query cli → For media components, mock jsdom gaps such as `HTMLMediaElement | — |
| `react-typescript` | — | — |

### salesforce-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `agentforce-2025` | — | — |
| `data-cloud-2025` | Identify use case → Map data sources → Define DMOs and matching → Build insights / segments → Activate → Validate | — |
| `flow-orchestrator-2025` | — | — |
| `hyperforce-2025` | — | — |
| `lightning-2025-features` | — | — |

### ssdt-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `sql-server-2025` | — | — |
| `ssdt-cicd-best-practices-2025` | — | — |
| `windows-git-bash-paths` | — | — |

### stripe-billing-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `stripe-credit-audit-trail` | — | — |
| `stripe-list-pagination-previous-attributes` | — | — |
| `stripe-refund-dispute-lifecycle` | — | — |
| `stripe-webhook-idempotency` | — | — |

### tailwindcss-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `tailwindcss-accessibility` | — | — |
| `tailwindcss-advanced-components` | — | — |
| `tailwindcss-advanced-design-systems` | — | — |
| `tailwindcss-advanced-layouts` | — | — |
| `tailwindcss-animations` | — | — |
| `tailwindcss-debugging` | — | — |
| `tailwindcss-framework-integration` | — | — |
| `tailwindcss-fundamentals-v4` | — | — |
| `tailwindcss-mobile-first` | Start with unprefixed utilities for the mobile baseline, then progress → Choose breakpoints from content needs rather than device names; overri → Use fluid typography and spacing with clamp() for smoother scaling b → Make interactive elements touch-safe with 44px recommended targets, ad → Use container queries for reusable components that must respond to the → Reserve media dimensions with aspect-ratio utilities and use safe-area | — |
| `tailwindcss-performance` | — | Only used styles (~10-50KB typical); { |
| `tailwindcss-plugins` | — | — |
| `tailwindcss-responsive-darkmode` | — | — |

### terraform-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `opentofu-guide` | — | — |
| `terraform-tasks` | — | — |

### test-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `vitest-3-features` | — | — |
| `windows-git-bash-testing` | — | — |

### tsql-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `advanced-patterns` | — | — |
| `azure-sql-optimization` | — | — |
| `execution-plan-analysis` | 1. Establish Plan Context → 2. Rank High-Cost Operators, Then Validate → 3. Check Scans, Seeks, and Residual Predicates → 4. Find Implicit Conversions and Collation Issues → 5. Compare Estimated vs Actual Rows → 6. Verify Partition Elimination → 7. Interpret Index Warnings Carefully → 8. Report Findings as Evidence | — |
| `index-strategies` | 1. Start from Query Shape → 2. Validate Data Types and SARGability → 3. Compare Existing Indexes → 4. Account for Change Constraints | — |
| `query-optimization` | 1. Schema-First Validation → 2. Identify the Root Bottleneck → 3. Fix SARGability and Type Mismatches → 4. Prove Join Changes → 5. Check Temp Tables and Staging Types → 6. Select the Rewrite Template | Respond with:; 1. Intake status: verified, unverified, disproved, needs diagnostic.; 2. Bottleneck evidence: plan nodes, reads, rows, estimates, warnings.; 3. Recommendation path: rewrite, index/stat change, or diagnostic, separated by allowed change type.; 4. Proof harness: result equivalence and before/after performance metrics.; 5. Risks: parameter sensitivity, write overhead, blocking, partition safety, remote pushdown. |
| `tsql-functions` | — | — |

### tui-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `framework-recipes` | — | — |
| `input-handling` | — | — |
| `platform-compatibility` | — | — |
| `rendering-layout-performance` | — | — |
| `terminal-standards` | — | — |
| `tui-fundamentals` | — | — |
| `tui-testing-debugging` | Reproduce with the smallest terminal size and input sequence → Capture raw input and output bytes when protocol behavior is suspected → Separate stdout, stderr, logs, and alternate-screen output → Disable animations and color to isolate layout from style → Test outside and inside tmux/screen/SSH if relevant → On Windows, test through ConPTY when Windows support is claimed | — |
| `tui-troubleshooting` | — | — |
| `tui-visual-design` | — | — |
| `unicode-color-accessibility` | — | — |
| `widgets-state-security-distribution` | — | — |

### unity-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `unity-csharp-scripting` | — | — |
| `unity-editor-tooling` | — | — |
| `unity-modding` | — | — |
| `unity-networking` | — | — |
| `unity-performance` | Build with Development Build + Autoconnect Profiler enabled → Profile on target device (not in Editor -- Editor overhead distorts re → Identify the bottleneck category → Drill into the specific system causing the issue → Optimize, re-profile, and compare | — |
| `unity-shaders-rendering` | — | — |
| `unity-ui-development` | — | — |

### viral-video-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `viral-video-hooks-retention` | — | — |
| `viral-video-long-form` | — | — |
| `viral-video-platform-algorithms` | — | — |
| `viral-video-short-form` | — | — |

### windows-path-master

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `windows-path-troubleshooting` | Step 1: Detect the Error → Step 2: Analyze the Path → Step 3: Request Clarification (If Needed) → Step 4: Convert and Retry → Step 5: Verify Success | S:\repos\myproject\src\components\Button.tsx; S:\repos\project\file.tsx; S:\repos\my-project\src\components\Button.tsx |

## Claude Skills

_454 skills._

### architect/architect-toolkit

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `architecture-anti-patterns` | Common Anti-Patterns and Recognition → Diagnose When Present → Guide Teams Away | — |
| `architecture-kata` | Read Problem → Identify Constraints → Quick Design → Document Decisions → Discuss & Refine | — |
| `architecture-patterns-catalog` | Identify Problem → Search Catalog → Evaluate Trade-offs → Choose Pattern(s) → Implement Carefully → Document | — |
| `architecture-review-facilitation` | Prepare → Start → Present → Clarify → Evaluate → Resolve → Decide → Document | — |
| `interview-prep` | Study Common Systems → Practice System Design Problem → Prepare Answers to Common Questions → Practice Communication → Mock Interviews | — |
| `system-audit` | Prepare Audit Checklist → Gather Information → Assess Each Area → Identify Patterns → Recommend Improvements → Document and Present | — |
| `technical-mentoring` | Understand Your Mentee → Establish Rhythm → Provide Feedback on Their Work → Assign Stretch Projects → Reflect and Adjust | — |

### architect/architecture-governance

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `architecture-principles` | Identify Core Values → Derive Principles → Make Principles Memorable → Create Decision Rules → Communicate and Enforce | — |
| `architecture-review-checklist` | Prepare Checklist → Conduct Review → Document Decision → Track Follow-Up → Iterate | — |
| `change-impact-analysis` | Trace Dependencies → Assess Direct Impact → Assess Indirect Impact → Calculate Risk Score → Plan Mitigation | — |
| `compliance-framework` | Identify Applicable Standards → Map Controls to Architecture → Design for Audit → Build Operational Processes → Plan for Verification | — |
| `dependency-governance` | Map Dependency Graph → Audit for Risk → Reduce Coupling → Version Management → Plan Deprecation | — |
| `fitness-function-design` | Identify Key Quality Attributes → Define Metrics for Each Attribute → Set Thresholds → Automate Checks → Monitor and Adjust | — |
| `tech-debt-assessment` | Catalog Debt Items → Quantify Impact → Estimate Paydown Effort → Calculate ROI → Prioritize | — |

### architect/communication

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `architecture-brief` | One-Pager Structure → Lead with Impact → Use Analogies → Acknowledge Uncertainty → Make it Scannable | — |
| `architecture-roadmap` | Identify Themes → Define Initiatives → Map Dependencies → Estimate Effort → Communicate Regularly | — |
| `c4-model-diagram` | Draw Context Diagram → Draw Container Diagram → Draw Component Diagram → Draw Code Diagram → Keep Diagrams Current | — |
| `context-diagram` | Draw Central Rectangle → Add External Systems → Add Actors → Label Data Flows → Keep Simple | — |
| `rfc-template` | RFC Header → Problem Section → Proposed Solution → Design Details → Alternatives | — |
| `sequence-diagram` | Identify Actors → Draw Time Axis → Draw Interactions → Example: Order Processing → Add Alternatives | — |
| `stakeholder-presentation` | Tailor to Audience → Structure → Visuals → Manage Q&A → Follow-Up | — |

### architect/data-architecture

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `data-flow-diagram` | Identify Data Sources → Map Transformations → Define Sinks and Destinations → Choose Processing Model → Diagram the Flow | — |
| `data-governance` | Define Data Owner Roles → Establish Metadata Catalog → Set Quality Standards → Build Data Dictionary → Implement Access Control | — |
| `data-model-design` | Identify Entities → Identify Attributes → Define Relationships → Normalize → Denormalize Strategically | — |
| `data-pipeline-design` | Choose Processing Model → Design Data Stages → Implement Quality Gates → Handle Failures and Recovery → Plan Monitoring and Alerting | — |
| `event-sourcing` | Identify Core Events → Design Event Schema → Plan Aggregate Boundaries → Implement Snapshot Strategy → Create Read Projections | — |
| `integration-patterns` | Choose Primary Pattern → Design Idempotency → Handle Schema Evolution → Implement Error Handling → Plan Monitoring and Alerting | — |
| `schema-evolution` | Plan Phase 1 (Additive) → Plan Phase 2 (Dual Write) → Plan Phase 3 (Migrate Data) → Plan Phase 4 (Code Switch) → Plan Phase 5 (Cleanup) | — |
| `storage-selection` | Catalog Data Requirements → Match Workload to Storage Type → Evaluate Consistency vs Availability → Project Operational Burden → Cost Analysis | — |

### architect/decision-making

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `architecture-decision-record` | Describe Problem → List Options → Explain Rationale → Document Consequences → Link Related Decisions | — |
| `build-vs-buy` | List Requirements → Compare Options → Cost Model → Risk Assessment → Decide | — |
| `legacy-modernization` | Assessment → Strangler Fig → Facade Layer → Refactoring → Incremental Value | — |
| `migration-strategy` | Assess Current State → Define Target State → Identify Seams → Plan Phases → Risk Mitigation → Success Metrics | — |
| `proof-of-concept-plan` | Define Hypothesis → Scope Tightly → Time-Box → Success Criteria → Go-No-Go Decision | — |
| `risk-assessment` | Identify Risks → Assess → Prioritize → Mitigate → Monitor | — |
| `technology-radar` | Assess Technology → Plot on Radar → Define Transition → Communicate | — |
| `vendor-evaluation` | Functional Requirements → Non-Functional → Business Terms → Risk Assessment → References | — |

### architect/infrastructure-design

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `capacity-planning` | Establish Baseline → Project Growth → Calculate Required Capacity → Model Scenarios → Plan Upgrades | — |
| `cloud-architecture` | Select Core Services → Design Resilient Architecture → Plan Networking → Implement Security → Cost Optimize | — |
| `container-orchestration` | Design Cluster Topology → Plan Node Sizing → Configure Storage → Set Up Networking → Plan Operations | — |
| `deployment-topology` | Choose Orchestration Platform → Design Service Topology → Implement Service Discovery → Plan Load Balancing → Configure Health Checks | — |
| `disaster-recovery-plan` | Define Business Requirements → Design Backup Strategy → Plan Failover → Document Procedures → Schedule Regular Testing | — |
| `infrastructure-as-code-patterns` | Choose Tool → Design Module Structure → Plan State Management → Implement Testing → Detect and Handle Drift | — |
| `multi-region-design` | Map User Distribution → Plan Data Replication → Implement Read Replicas → Set Up Failover → Optimize Latency | — |
| `network-topology` | Design VPC → Segment with Security Groups → Plan Load Balancing → Set Up DNS → Implement DDoS Protection | — |

### architect/quality-attributes

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `cost-optimization` | Measure Current Costs → Baseline Cost per Unit → Identify Optimization Opportunities → Model Impact → Implement & Monitor | — |
| `maintainability-assessment` | Measure Code Quality → Assess Coupling → Evaluate Testability → Identify Tech Debt → Design for Evolution | — |
| `observability-design` | Define Key Metrics → Design Metrics Collection → Configure Logging → Implement Distributed Tracing → Build Dashboards & Alerts | — |
| `performance-modeling` | Measure Current Performance → Build Queueing Model → Identify Breaking Points → Model Optimizations → Compare Trade-offs | — |
| `reliability-design` | Define SLA/SLO/SLI → Map Failure Modes → Design Fault Isolation → Plan Recovery → Establish Monitoring | — |
| `scalability-analysis` | Establish Baseline → Project Growth → Identify Bottlenecks → Model Scaling Scenarios → Project Costs | — |
| `security-architecture` | Threat Model → Design Authentication → Design Authorization → Protect Data → Audit & Monitor | — |
| `trade-off-analysis` | List Options → Define Evaluation Criteria → Score Each Option → Calculate Weighted Scores → Qualitative Analysis | — |

### architect/system-design

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `api-gateway-design` | Define Gateway Responsibilities → Design Routing Rules → Implement Authentication → Configure Rate Limiting → Handle Response Aggregation | — |
| `caching-strategy` | Map Access Patterns → Design Multi-Layer Cache → Choose Cache Policy → Define Invalidation Strategy → Establish Metrics | — |
| `cqrs-design` | Analyze Read vs Write → Design Command Model → Design Read Models → Define Synchronization → Handle Eventual Consistency | — |
| `data-partitioning` | Choose Partition Key → Select Partitioning Scheme → Plan Rebalancing → Handle Hot Partitions → Define Consistency Model | — |
| `domain-driven-design` | Extract Ubiquitous Language → Sketch Bounded Contexts → Design Aggregates → Model Value Objects → Event Storm | — |
| `event-driven-architecture` | Define Events → Design Producer & Consumer → Choose Messaging Infrastructure → Handle Event Versioning → Establish Observability | — |
| `microservices-patterns` | Map Distributed Transactions → Choose Saga Style → Apply Resilience Patterns → Design Idempotency → Establish Observability | — |
| `monolith-assessment` | Score Pain Dimensions → Map Team Structure → Identify Seams → Cost-Benefit Analysis → Choose Evolution Path | — |
| `service-mesh-patterns` | Assess Mesh Necessity → Design Sidecar Injection → Configure Routing & Load Balancing → Implement Resilience Policies → Enable Observability | — |
| `system-decomposition` | — | When decomposing, deliver:; 1. Business Capabilities: What the system does; 2. Bounded Contexts: Explicit boundaries with names; 3. Context Diagram: Visual showing contexts and integration; 4. Ubiquitous Language: Key terms per context; 5. Integration Patterns: Sync/Async by integration point; 6. Cohesion/Coupling Assessment: Scores for each context; 7. Deployment Plan: How to implement decomposition |

### designer/design-ops

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `design-critique` | — | — |
| `design-qa-checklist` | — | — |
| `design-review-process` | — | — |
| `design-sprint-plan` | — | — |
| `handoff-spec` | — | — |
| `team-workflow` | What You Do → Workflow Components → Workflow Stages → Best Practices | — |
| `version-control-strategy` | — | — |

### designer/design-research

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `affinity-diagram` | Extract data points → 2. Bottom-up clustering | — |
| `card-sort-analysis` | Understand the study → 2. Analyze groupings | — |
| `diary-study-plan` | Define research goals → 2. Design the study | — |
| `empathy-map` | — | — |
| `interview-script` | — | — |
| `jobs-to-be-done` | — | — |
| `journey-map` | — | — |
| `summarize-interview` | Read the transcript → 2. Create a structured summary with | — |
| `usability-test-plan` | Define objectives → 2. Create the test plan with | — |
| `user-persona` | — | — |

### designer/design-systems

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `accessibility-audit` | — | — |
| `component-spec` | — | — |
| `design-token` | — | — |
| `documentation-template` | — | — |
| `icon-system` | — | — |
| `naming-convention` | — | — |
| `pattern-library` | — | — |
| `theming-system` | — | — |

### designer/designer-toolkit

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `case-study` | — | — |
| `design-rationale` | — | — |
| `design-system-adoption` | — | — |
| `design-token-audit` | — | — |
| `presentation-deck` | — | — |
| `ux-writing` | — | — |

### designer/interaction-design

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `animation-principles` | — | — |
| `error-handling-ux` | — | — |
| `feedback-patterns` | — | — |
| `gesture-patterns` | — | — |
| `loading-states` | — | — |
| `micro-interaction-spec` | — | — |
| `state-machine` | — | — |

### designer/prototyping-testing

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `a-b-test-design` | — | — |
| `accessibility-test-plan` | — | — |
| `click-test-plan` | — | — |
| `heuristic-evaluation` | — | — |
| `prototype-strategy` | — | — |
| `test-scenario` | — | — |
| `user-flow-diagram` | — | — |
| `wireframe-spec` | — | — |

### designer/ui-design

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `color-system` | — | — |
| `dark-mode-design` | — | — |
| `data-visualization` | — | — |
| `illustration-style` | — | — |
| `layout-grid` | — | — |
| `responsive-design` | — | — |
| `spacing-system` | — | — |
| `typography-scale` | — | — |
| `visual-hierarchy` | — | — |

### designer/ux-strategy

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `competitive-analysis` | — | Summary overview, comparison matrix, competitor profiles, opportunity map, annotated references. |
| `design-brief` | — | — |
| `design-principles` | Gather inputs (research, values, strategy) → Workshop to surface candidates → Draft and debate ('Would anyone disagree?') → Prioritize for conflicts → Test against past decisions → Socialize widely | — |
| `experience-map` | — | — |
| `metrics-definition` | — | — |
| `north-star-vision` | — | — |
| `opportunity-framework` | — | Ranked list with rationale, theme groupings, dependencies, confidence levels. |
| `stakeholder-alignment` | — | — |

### engineer/api-development

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `api-documentation` | Write OpenAPI Spec → Include Examples → Document Errors → Explain Auth → Rate Limits → Generate Docs → Test Docs | — |
| `api-error-handling` | Use Right Status Code → Consistent Format → Specific Codes → Retry Guidance → Request ID → Human & Machine → Document | — |
| `api-testing-strategy` | Contract Tests → Happy Path → Error Cases → Edge Cases → Integration → Load → Chaos | — |
| `api-versioning-strategy` | Choose Strategy → Plan Deprecation → Use Deprecated Headers → Avoid Removing → Test Compatibility → Document Sunset | — |
| `graphql-schema-design` | Define Types → Design Queries → Design Mutations → Use Enums → Use Interfaces → Plan Subscriptions → Document Null | — |
| `grpc-service-design` | Define Messages → Define Services → Choose RPC Types → Plan Deadlines → Error Handling → Streaming | — |
| `rate-limiting-design` | Set Limits → Choose Algorithm → Communicate Limits → Handle Overages → Exempt Authenticated → Monitor | — |
| `rest-api-design` | — | When designing an API, deliver:; 1. Resource List: What resources does the API expose?; 2. Endpoint Matrix: Methods × resources; 3. Request/Response Examples: Concrete JSON examples; 4. Error Handling: Standard error format; 5. Idempotency Strategy: How to handle retries; 6. Pagination Strategy: How to handle large collections |

### engineer/code-quality

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `clean-code-review` | Check Names → Analyze Functions → Inspect Duplication → Review Comments → Verify Error Handling → Check Formatting → Assess Cohesion → Look for Side Effects | — |
| `code-complexity-analysis` | Count Decisions → Check Nesting → Identify Polymorphism Opportunities → Extract Complex Conditions → Break Long Methods → Use Early Returns → Reduce Parameters → Test Complexity | — |
| `code-smell-detector` | Long Methods → Duplicated Code → Long Parameter Lists → Data Clumps → Switch Statements → Primitive Obsession → Lazy Classes → Comments | — |
| `dependency-injection` | Identify Hard Dependencies → Declare Dependencies → Make Testable → Use Interfaces → Avoid Service Locator → Document Contracts → Keep Constructors Simple → Validate Dependencies | — |
| `error-handling-patterns` | Identify Error Boundaries → Choose Exception Type → Include Context → Plan Recovery → Document Throws → Test Error Paths → Avoid Silent Failures → Use Error Enums | — |
| `function-design` | Identify Purpose → Count Parameters → Check for Side Effects → Verify Purity → Measure Cohesion → Review Return Value → Check Error Handling → Test Independence | — |
| `interface-design` | Identify Clients → List Required Methods → Check Cohesion → Verify Minimal → Document Contracts → Check Mutability → Review Generics → Plan Evolution | — |
| `naming-conventions` | Variables → Functions → Classes → Constants → Boolean Variables → Avoid Abbreviations → Scope Rule → Domain Language | — |
| `refactoring-catalog` | — | When using this skill, deliver:; 1. Refactoring Identified: What refactoring technique is being applied? Why?; 2. Before Code: Original code showing the problem; 3. After Code: Refactored code showing the improvement; 4. Verification: Tests still pass; behavior unchanged; 5. Commit Message: Conventional commit format; Example output:; ` |
| `solid-principles` | Identify Responsibilities → Check Inheritance → Review Interfaces → Examine Dependencies → Look for Extensions → Validate Contracts → Measure Cohesion | — |

### engineer/database-engineering

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `connection-pool-management` | Min/Max Size → Max = (Number of Cores \* 2) + Extra for I/O → Connection Lifetime → Idle Timeout → Health Checks → Queue Size → Monitoring | — |
| `data-integrity-patterns` | NOT NULL → UNIQUE → FOREIGN KEYS → CHECK → Triggers → Audit Trail → Enforcement | — |
| `index-design` | Index WHERE Clauses → Index JOIN Columns → Index ORDER BY → Composite Order → Covering Indexes → Monitor → Remove Unused | — |
| `migration-strategy` | Plan Migration → Add Column Nullable → Migrate Data → Remove Old Column → Test Rollback → Run on Read Replica → Monitor | — |
| `query-optimization` | Identify Slow Queries → Get EXPLAIN PLAN → Look for Scans → Add Indexes → Verify Join Order → Rewrite if Needed → Monitor | — |
| `schema-design` | Identify Entities → Identify Relationships → Normalize → Keys → Types → Constraints → Indexes | — |
| `transaction-management` | Identify Invariants → Transaction Scope → Isolation Level → Lock Order → Timeout → Error Handling → Monitoring | — |

### engineer/debugging

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `binary-search-debugging` | Identify Good and Bad Commits → Run Git Bisect → Test at Bisect Point → Bisect Reports → Find Exact Commit → Review Commit → Code Path Bisect | — |
| `concurrency-debugging` | Reproduce Consistently → Check Synchronization → Verify Lock Ordering → Analyze Thread Dumps → Look for Wait-Free Patterns → Use Tools → Add Happens-Before | — |
| `log-analysis` | Establish Timeline → Filter Noise → Find Correlation → Look for Cascades → Check Systems → Extract Variables → Visualize | — |
| `memory-leak-detection` | Establish Baseline → Create Heap Dump → Analyze Dump → Find Retention Path → Trace to Root → Identify Culprit → Fix | — |
| `performance-profiling` | Start Profiler → Run Under Load → Collect Data → Analyze Output → Identify Hot Spots → Drill Down → Measure Impact | — |
| `postmortem-analysis` | Gather Facts → Create Timeline → Document Context → RCA → Prevention → Write Postmortem → Define Action Items | — |
| `root-cause-analysis` | Identify Symptom → Ask Why → Repeat → Categorize → Identify Root → Verify | — |
| `systematic-debugging` | — | When using this skill, deliver:; 1. Bug Summary: What was reported?; 2. Reproduction Steps: How to make it happen; 3. Hypothesis: What you think went wrong; 4. Experiment: Minimal test to verify hypothesis; 5. Result: What you found; 6. Root Cause: Why the bug happened; 7. Fix: Code changes to address root cause; 8. Verification: Tests proving bug is fixed; 9. Commit: Commit message with bug fix; Example output:; ` |

### engineer/devops-practices

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `alerting-strategy` | Define SLOs → Measure Error Budget → Alert on SLO → Runbooks → Tuning → Escalation → Blameless Postmortems | — |
| `ci-cd-pipeline-design` | Identify Stages → Define Triggers → Parallelize → Cache → Gate → Secrets → Artifacts | — |
| `deployment-strategy` | Blue-Green → Canary → Rolling → Feature Flags → Monitor → Rollback → Incidents | — |
| `dockerfile-best-practices` | Choose Base Image → Install Essentials → Use Multi-Stage → Order Statements → Run as Non-Root → Health Checks → Documentation | — |
| `feature-flag-design` | Keep Simple → Owner → Expiration → Rollout → Monitoring → Cleanup → Config | — |
| `infrastructure-as-code` | Use IaC → Version Control → Code Review → Modules → Secrets → State → Testing | — |
| `log-aggregation` | Structured Logging → Trace ID → Log Levels → Centralization → Filtering → Retention → Performance | — |
| `monitoring-instrumentation` | Define SLOs → Metrics → Logs → Traces → Dashboards → Alerts → Runbooks | — |

### engineer/engineer-toolkit

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `code-review-checklist` | Correctness → Tests → Code Quality → Performance → Security → Comments → Approval | — |
| `documentation-strategy` | README → Architecture → API → Runbooks → ADR → Keep Current → Searchable | — |
| `git-workflow` | Branch Naming → Commits → Commit Messages → Rebase → PR → Merge Strategy → Cleanup | — |
| `incident-response` | Assess Severity → Declare Incident → Assign Roles → War Room → Diagnosis → Fix → Status Page | — |
| `on-call-runbook` | Identify Alert → Severity → First Steps → Diagnosis → Actions → Escalation → Communication | — |
| `pair-programming-guide` | Establish Roles → Switch Regularly → Communicate → Take Breaks → Use Tools → No Passive Navigation → Evaluate | — |
| `technical-writing` | Know Your Audience → Start with Purpose → Use Examples → Be Concrete → Structure Clearly → Diagrams → Keep Current | — |

### engineer/implementation-patterns

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `algorithm-analysis` | Count Operations → Dominant Term → Compare Algorithms → Consider Constants → Measure → Choose | — |
| `concurrency-patterns` | Shared Memory → Actor Model → CSP → Async/Await → Lock-Free → Choose Wisely | — |
| `data-structure-selection` | Analyze Access Patterns → Identify Bottleneck → Compare Options → Benchmark → Choose → Monitor | — |
| `design-patterns` | Identify Problem → Map to Pattern → Understand Intent → Consider Tradeoffs → Implement → Refine | — |
| `functional-patterns` | Prefer Pure Functions → Compose Functions → Use Higher-Order → Embrace Immutability → Handle Effects → Test Easily | — |
| `reactive-patterns` | Model Data as Streams → Use Operators → Handle Backpressure → Error Handling → Lifecycle → Test | — |
| `resource-management` | Use RAII → Or Try-Finally → Or Defer → Test Cleanup → Avoid Leaks → Document Ownership | — |
| `state-management` | Define States → Define Transitions → Model Constraints → Event Sourcing → Separate Reads → Test Transitions | — |

### engineer/testing

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `integration-test-design` | Identify Interactions → Start with Real Dependencies → Create Test Factories → Test Key Flows → Verify Contracts → Handle Cleanup → Accept Slowness | — |
| `mutation-testing` | Run Baseline → Inject Mutations → Run Tests → Identify Survivors → Strengthen Tests → Repeat | — |
| `performance-test-plan` | Define SLAs → Create Load Profile → Measure Baseline → Profile Hot Paths → Set Thresholds → Run Regularly → Compare Versions | — |
| `property-based-testing` | Identify Invariants → Choose Generators → Write Property → Run Generator → Shrink Failures → Document Examples | — |
| `tdd-workflow` | Context → Domain Context → When to Use This Skill → Prerequisites → Instructions (Detailed) → Output Format → Red: Write Test → Green: Implement → Verify → Refactor (if needed) → Next Cycle → Worked Example → Decision Framework → Anti-Patterns (Expanded) → Quality Checklist → Further Reading | When using this skill, deliver:; 1. Test Code: Failing test demonstrating desired behavior (Red); 2. Implementation: Minimal code passing the test (Green); 3. Refactored Code: Improved implementation if duplication emerged (Refactor); 4. Test Suite Status: All tests passing, no regressions; 5. Next Test: What behavior should the next test verify?; Example output structure:; ` |
| `test-data-management` | Choose Strategy → Use Builders for Complex Objects → Create Factories for Common Patterns → Avoid Shared State → Seed Data Carefully → Document Defaults → Performance | — |
| `test-doubles-strategy` | Stub → Mock → Fake → Spy → Dummy → Avoid Over-Mocking → Prefer Fakes | — |
| `test-strategy` | — | When planning tests, deliver:; 1. Test Pyramid: Counts for unit/integration/E2E; 2. Coverage Targets: By risk area; 3. Unit Test Plan: What functions, what cases; 4. Integration Test Plan: What flows, what dependencies; 5. E2E Test Plan: Which user journeys; 6. Test Data: How to set up test data; 7. Success Criteria: What passing tests prove |
| `unit-test-design` | Identify Unit → Mock Dependencies → Arrange → Act → Assert → Name Clearly → Test Edge Cases | — |

### product-manager/analytics

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `a-b-test-design-pm` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |
| `cohort-analysis` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |
| `data-storytelling` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |
| `experiment-design` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |
| `funnel-analysis` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |
| `metrics-framework` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |
| `north-star-metric` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |
| `retention-analysis` | Define success metrics → Identify leading indicators → Set targets → Establish baseline → Monitor regularly → Investigate changes | Metrics framework or experiment plan including:; Key metrics and definitions; Baseline and targets; Data collection method; Review cadence; Success criteria |

### product-manager/discovery

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `assumption-mapping` | List all assumptions → Categorize by type → Rank by risk → Design cheap tests → Identify dependencies → Plan sequence | Assumption mapping (2-3 pages):; List of all assumptions (50-100 per product); Risk ranking (color-coded); Validation test for high-risk assumptions; Success criteria for each; Estimated cost/timeline |
| `competitive-landscape` | Map direct competitors → Map alternatives → Create feature comparison → Identify moats → Assess market maturity → Find whitespace | Competitive landscape report (2-3 pages):; Competitive matrix (features, pricing, positioning); Direct vs. indirect competitors; Strengths, weaknesses, opportunities per competitor; Identified whitespace; Recommended positioning differentiation |
| `customer-interview-guide` | Define the interview goal → Select participants → Structure the interview → Prepare questions → Document learning | Customer interview guide (2-3 pages) with:; Interview goals; Target customer profile; Warm-up conversation starters; Structured question set; Probing techniques; Note-taking template; Post-interview synthesis framework |
| `customer-segmentation` | Gather data → Identify variables → Create personas → Validate differences → Prioritize segments → Define targeting | Segmentation document (2-3 pages):; Segment definitions and personas; Size estimates for each; Shared needs/pain points; Decision triggers (why they buy); Recommended positioning per segment; Prioritization rationale |
| `discovery-sprint-plan` | Define sprint goal → Plan activities → Assign owners → Schedule interviews → Gather baseline data → Plan synthesis | Discovery sprint plan (1-2 pages) + Daily standup template:; Sprint goal (one question); Success criteria (how will we know we've learned?); Activities per day (interviews, data gathering, synthesis); Assigned owners and deliverables; Daily stand-up questions template; Synthesis and recommendation format |
| `market-sizing` | Define TAM (top-down) → Define SAM → Define SOM → Calculate multiple ways → Document assumptions → Sensitivity analysis | Market sizing document (2 pages):; TAM estimate and derivation; SAM estimate (your addressable market); SOM projection (1-3 years); Key assumptions (documented); Sensitivity analysis; Sources and confidence levels |
| `opportunity-assessment` | Size the opportunity → Assess urgency → Validate importance → Check addressability → Identify dependencies → Test willingness to pay → Evaluate trend | Opportunity assessment (1-2 pages):; Problem statement; Market size (TAM/SAM/SOM with sources); Customer urgency (quotes, data); Competitive landscape; Addressability (constraints, strengths); Investment required; Recommendation (pursue/deprioritize/monitor) |
| `pain-point-analysis` | List all pain points → Categorize → Score each → Assess addressability → Estimate impact → Identify dependencies | Pain point analysis (2-3 pages):; Ranked list of pains (frequency × intensity × reach); Supporting quotes from customers; Addressability assessment per pain; Business impact if solved; Recommended priority order |
| `problem-statement` | 1. Gather and Synthesize Evidence → 2. Identify the Core Friction (Not the Symptom) → 3. Define the Customer Segment Precisely → 4. Quantify Impact (Business + Emotional) → 5. Write the Problem Statement → 6. Stress-Test Your Problem Statement | A 1-2 page problem statement document (sharable with engineering, design, stakeholders):; ` |
| `voice-of-customer` | Define sources → Collect systematically → Analyze for patterns → Distinguish signal from noise → Prioritize insights → Close the loop | Voice of Customer report (2-3 pages):; Key feedback themes (with quote evidence); Volume and reach of each theme; Segment breakdowns (who mentioned what); Business impact per theme; Recommended actions; Feedback loop closure plan |

### product-manager/launch

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `beta-program-design` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |
| `feature-flag-strategy` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |
| `go-to-market-strategy` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |
| `launch-plan` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |
| `launch-readiness-checklist` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |
| `release-notes` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |
| `rollout-strategy` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |
| `success-criteria` | Define launch goals → Identify audiences → Plan timeline → Coordinate teams → Prepare messaging → Setup monitoring | Launch plan including:; Timeline and milestones; Target audiences and messaging; Channel strategy; Success metrics; Contingency plans |

### product-manager/pm-toolkit

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `customer-advisory-board` | Understand the practice → Prepare thoroughly → Facilitate clearly → Document outcomes → Follow up → Iterate | Structured output appropriate to the activity:; Agenda or framework; Participant list; Pre-work materials; Summary of decisions/actions; Follow-up items and owners |
| `one-pager` | Understand the practice → Prepare thoroughly → Facilitate clearly → Document outcomes → Follow up → Iterate | Structured output appropriate to the activity:; Agenda or framework; Participant list; Pre-work materials; Summary of decisions/actions; Follow-up items and owners |
| `pm-interview-prep` | Understand the practice → Prepare thoroughly → Facilitate clearly → Document outcomes → Follow up → Iterate | Structured output appropriate to the activity:; Agenda or framework; Participant list; Pre-work materials; Summary of decisions/actions; Follow-up items and owners |
| `product-brief` | Understand the practice → Prepare thoroughly → Facilitate clearly → Document outcomes → Follow up → Iterate | Structured output appropriate to the activity:; Agenda or framework; Participant list; Pre-work materials; Summary of decisions/actions; Follow-up items and owners |
| `product-ops-playbook` | Understand the practice → Prepare thoroughly → Facilitate clearly → Document outcomes → Follow up → Iterate | Structured output appropriate to the activity:; Agenda or framework; Participant list; Pre-work materials; Summary of decisions/actions; Follow-up items and owners |
| `product-review` | Understand the practice → Prepare thoroughly → Facilitate clearly → Document outcomes → Follow up → Iterate | Structured output appropriate to the activity:; Agenda or framework; Participant list; Pre-work materials; Summary of decisions/actions; Follow-up items and owners |
| `retrospective-facilitation` | Understand the practice → Prepare thoroughly → Facilitate clearly → Document outcomes → Follow up → Iterate | Structured output appropriate to the activity:; Agenda or framework; Participant list; Pre-work materials; Summary of decisions/actions; Follow-up items and owners |

### product-manager/prioritization

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `cost-of-delay` | List opportunities → Estimate delay cost → Estimate effort → Calculate Cost of Delay / Effort → Adjust for risk → Prioritize | Cost of Delay analysis (1-2 pages):; Opportunities with estimated delay costs; Effort estimates; Cost of Delay / Effort ratios; Prioritized list with rationale; Monthly revenue/churn impact if deprioritized |
| `impact-effort-matrix` | List all opportunities → Estimate Impact → Estimate Effort → Plot on 2x2 → Categorize → Plan sequencing | Impact-Effort Matrix (visual):; 2x2 grid with opportunities plotted; Quick wins highlighted (top-left); Strategic bets identified (top-right); Avoids called out (bottom-right) |
| `kano-analysis` | List all features → Functional questions → Dysfunctional questions → Plot responses → Understand satisfaction curves | Kano analysis chart:; Features classified (Basic, Performance, Delighter); Satisfaction curves visualized; Prioritization implications; Roadmap sequencing (Basics first, then Performance, then Delighters) |
| `moscow-prioritization` | List all features for the release → Stakeholder alignment → Categorize each feature → Review Must-haves → Quantify effort → Plan scope | MoSCoW prioritization list (1-2 pages):; Features categorized by MoSCoW; Effort estimate per category; Release scope and risks; Post-release backlog (Should/Could moved out) |
| `opportunity-scoring` | List customer needs/pain points → Score Importance → Score Satisfaction → Estimate Market Size → Calculate score → Plot heat map | Opportunity scoring matrix:; Needs/pain points scored; Heat map of opportunities; Top opportunities highlighted; Competitive context for each |
| `rice-scoring` | 1. List All Opportunities → 2. Define Scoring Parameters (Team Calibration) → 3. Score Each Opportunity → 4. Identify Scoring Patterns → 5. Rank & Review → 6. Plan Roadmap | A RICE scoring spreadsheet (shared with team) + a 1-page summary:; ` |
| `roadmap-design` | Choose format → Communicate strategy → Highlight dependencies → Set expectations → Plan reviews → Share transparently | Product roadmap (visual + document):; Strategic themes or horizons; Quarterly (or quarterly) priorities; Key dependencies; Stated uncertainty and assumptions; Review cadence and process |
| `weighted-scoring` | Identify evaluation criteria → Assign weights → Score each opportunity → Calculate total score → Rank and validate → Adjust weights | Weighted scoring model (1-2 pages):; Evaluation criteria and weights; Scoring rubric (how to score each criterion); Opportunities scored and ranked; Top priorities with rationale |

### product-manager/requirements

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `acceptance-criteria` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |
| `definition-of-done` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |
| `edge-case-analysis` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |
| `epic-breakdown` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |
| `feature-specification` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |
| `jobs-to-be-done-pm` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |
| `prd-template` | 1. Problem & Context (1 paragraph) → 2. Success Metrics (Table Format) → 3. User Stories or Customer Jobs → 4. Requirements (Detailed) → 5. Edge Cases & Boundaries → 6. Constraints & Assumptions → 7. Design Specifications (Link to Design Docs) → 8. Success Criteria & Testing | A 4-6 page document including:; 1. Executive Summary (1 paragraph): What problem? Why this solution? Expected business impact?; 2. Problem Statement (link to discovery doc); 3. Success Metrics (table); 4. User Stories (5-8 concise stories); 5. Requirements (functional + non-functional, organized by feature area); 6. Edge Cases (table); 7. Constraints (bulleted); 8. Design Specs (wireframe links + high-level flow); 9. Acceptance Criteria (testable checklist); 10. Dependencies (what teams/systems are affected?); 11. Timeline (phases: design review, engineering, QA, launch) |
| `requirements-traceability` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |
| `user-story-mapping` | Start with the job → Define success → Document constraints → Define edge cases → Get feedback | Requirements specification including:; Customer job/context; Success criteria; Technical constraints; Edge cases and assumptions |

### product-manager/stakeholder-management

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `change-management` | Understand stakeholders → Tailor messaging → Share rationale → Listen for concerns → Document decisions → Follow up | Stakeholder communication plan or update including:; Decision/update explained clearly; Rationale and trade-offs considered; Impact on different groups; How to provide feedback; Next steps and timeline |
| `cross-functional-alignment` | Understand stakeholders → Tailor messaging → Share rationale → Listen for concerns → Document decisions → Follow up | Stakeholder communication plan or update including:; Decision/update explained clearly; Rationale and trade-offs considered; Impact on different groups; How to provide feedback; Next steps and timeline |
| `decision-log` | Understand stakeholders → Tailor messaging → Share rationale → Listen for concerns → Document decisions → Follow up | Stakeholder communication plan or update including:; Decision/update explained clearly; Rationale and trade-offs considered; Impact on different groups; How to provide feedback; Next steps and timeline |
| `executive-summary` | Understand stakeholders → Tailor messaging → Share rationale → Listen for concerns → Document decisions → Follow up | Stakeholder communication plan or update including:; Decision/update explained clearly; Rationale and trade-offs considered; Impact on different groups; How to provide feedback; Next steps and timeline |
| `feedback-synthesis` | Understand stakeholders → Tailor messaging → Share rationale → Listen for concerns → Document decisions → Follow up | Stakeholder communication plan or update including:; Decision/update explained clearly; Rationale and trade-offs considered; Impact on different groups; How to provide feedback; Next steps and timeline |
| `stakeholder-map` | Understand stakeholders → Tailor messaging → Share rationale → Listen for concerns → Document decisions → Follow up | Stakeholder communication plan or update including:; Decision/update explained clearly; Rationale and trade-offs considered; Impact on different groups; How to provide feedback; Next steps and timeline |
| `status-update` | Understand stakeholders → Tailor messaging → Share rationale → Listen for concerns → Document decisions → Follow up | Stakeholder communication plan or update including:; Decision/update explained clearly; Rationale and trade-offs considered; Impact on different groups; How to provide feedback; Next steps and timeline |

### product-manager/strategy

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `business-model-canvas` | Value proposition → Customer segments → Channels → Customer relationships → Revenue streams → Key resources → Key activities → Key partnerships → Cost structure | Business Model Canvas (1 page):; 9-block visual layout; Unit economics summary (LTV, CAC); Key assumptions and dependencies; Strategic options and pivots to consider |
| `okr-definition` | Define company objectives → Set key results → Assign ownership → Cascade down → Make them ambitious → Review monthly | OKR document (2-3 pages):; Company Objectives and Key Results; Team OKRs (product, engineering, marketing, etc.); Definitions of success for each KR; Tracking cadence and review process; Expected outcomes if OKRs achieved |
| `positioning-statement` | Define target segment → Identify the need → State the alternative → Articulate differentiation → Connect to emotion → Test with customers | Positioning statement document (1-2 pages):; Target customer segment; Primary need/job; Competitive set; Unique differentiation (3-5 points); Emotional/rational benefits; Recommended messaging framework; Segment-specific variations (if multiple segments) |
| `product-market-fit` | Define PMF for your segment → Identify leading indicators → Set PMF thresholds → Measure today → Identify gaps → Plan improvements | PMF measurement framework (1-2 pages):; PMF indicators (metrics that prove PMF); Current state vs. targets; Leading indicators of PMF; Planned improvements and expected impact; Measurement plan and frequency |
| `product-strategy` | Define strategic direction → Articulate the bet → Identify trade-offs → Map to vision → Set success measures → Define time horizons | Product strategy document (2-3 pages):; Strategic direction and bets; Trade-offs and what we're not doing; Success measures per bet; Resource allocation (% to core vs. new); Roadmap implications; Risk factors and contingencies |
| `product-vision` | 1. Define the Customer Outcome (Not the Product) → 2. Articulate the Shift → 3. Ground in Reality → 4. Make It Inspiring → 5. Write the Vision Statement (1-3 sentences) → 6. Define the Customer Outcome Enabled → 7. Identify Market Assumptions → 8. Draft the Roadmap Implication (How do we get there?) | A 1-2 page vision document:; ` |
| `strategic-narrative` | Start with the problem → Introduce the solution → Show the impact → Connect to vision → Inspire action → Make it coherent | Strategic narrative (2-3 pages):; Problem framing; Solution introduced; Market opportunity; Vision connection; Call to action for different audiences (team, customers, investors) |
| `value-proposition` | Identify specific benefits → Quantify when possible → Acknowledge trade-offs → Map benefits to customer outcomes → Validate with customers → Differentiate vs. alternatives | Value proposition document (1-2 pages):; Top 3-5 customer benefits; Quantified value per benefit (time/cost/outcome); Trade-offs and considerations; Customer segments where value is highest; Pricing implications |

### qa-engineer/accessibility-testing

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `accessibility-regression` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `accessibility-test-plan` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `aria-validation` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `color-contrast-analysis` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `keyboard-navigation-testing` | Inventory interactive elements → Test tab order → Test focus visibility → Test keyboard interactions → Test keyboard traps → Test skip navigation | — |
| `screen-reader-testing` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `wcag-audit` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |

### qa-engineer/api-testing

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `api-mock-strategy` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `api-performance-testing` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `api-regression-suite` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `api-security-testing` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `api-test-plan` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `contract-testing` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `schema-validation` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |

### qa-engineer/automation

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `api-test-automation` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `automation-architecture` | Define Goals → Design Layers → Choose Patterns → Plan Tool Stack → Document and Evolve | — |
| `data-driven-testing` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `flaky-test-remediation` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `keyword-driven-testing` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `page-object-model` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `test-framework-selection` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `test-maintenance-strategy` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `visual-regression-testing` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |

### qa-engineer/functional-testing

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `boundary-value-analysis` | Identify Boundaries → Select Test Values → Design Boundary Tests → Execute and Document → Extend to Combinations | — |
| `decision-table-testing` | Identify Conditions and Actions → Create Decision Table → Design Tests → Execute and Validate → Review Completeness | — |
| `equivalence-partitioning` | Identify Partitions → Select Representative Values → Create Partition Matrix → Design Test Cases → Validate Coverage | — |
| `error-guessing` | Build a fault taxonomy → Mine defect history → Map risk hotspots → Design targeted tests → Prioritize by impact → Document and systematize | — |
| `exploratory-testing-charter` | Define Mission → Prepare Environment → Execute Charter → Document Findings → Debrief and Learn | — |
| `state-transition-testing` | Model the state machine → Build the state transition table → Derive 0-switch coverage tests → Derive 1-switch coverage tests → Test invalid transitions → Test guard conditions | — |
| `test-case-design` | Analyze Requirements → Apply Design Techniques → Create Test Cases → Review Test Cases → Organize Test Cases | — |
| `use-case-testing` | Enumerate use cases → Map the main success scenario → Extract alternate paths → Extract exception paths → Compose end-to-end scenarios → Build a use case / test matrix | — |

### qa-engineer/performance-testing

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `bottleneck-analysis` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `capacity-planning-qa` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `endurance-test-plan` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `load-test-design` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `performance-baseline` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `performance-test-report` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `spike-test-plan` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `stress-test-plan` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |

### qa-engineer/qa-toolkit

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `bug-report-template` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `qa-knowledge-base` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `qa-onboarding` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `qa-retrospective` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `release-readiness-assessment` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `test-environment-management` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `test-plan-review` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |

### qa-engineer/quality-metrics

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `defect-analysis` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `defect-prevention` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `escaped-defect-analysis` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `quality-dashboard` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `quality-gate-design` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `root-cause-analysis-qa` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `test-effectiveness-measurement` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |
| `test-metrics-framework` | Understand the Approach → Assess Current State → Design Application → Implement → Monitor and Improve | — |

### qa-engineer/test-strategy

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `regression-strategy` | Establish Regression Test Baseline → Implement Change-Based Test Selection → Create Regression Test Priorities → Automate Regression Tests → Review and Refactor Regularly | — |
| `risk-based-test-plan` | Identify Risk Sources → Assess Risk Probability and Impact → Prioritize by Risk Level → Design Risk-Mitigation Tests → Track and Adjust | — |
| `shift-left-strategy` | Assess Current Test Timing → Design Developer Testing Program → Integrate QA in Design Phase → Establish Quality Gates → Measure Shift-Left Impact | — |
| `test-coverage-analysis` | Select Coverage Dimensions → Establish Coverage Baselines → Identify Coverage Gaps → Design Gap-Closing Tests → Monitor Coverage Trends | — |
| `test-data-strategy` | Analyze Data Requirements → Design Data Sources → Implement Data Masking → Automate Data Provisioning → Plan Data Lifecycle | — |
| `test-environment-plan` | Define Environment Requirements → Design Environment Strategy → Plan Data Management → Implement Environment Provisioning → Establish Environment Maintenance | — |
| `test-estimation` | Understand Scope and Complexity → Estimate Test Case Creation → Estimate Test Execution → Estimate Automation Development → Validate with Historical Data | — |
| `test-pyramid-design` | Understand Application Architecture → Define Test Level Boundaries → Calculate Target Distribution → Design Testing Strategy per Level → Plan Pyramid Evolution | — |
| `test-strategy-design` | Understand Project Context → Identify Testing Scope → Map Risks and Priorities → Design Test Levels and Balance → Document Testing Approach | — |

### sdlc

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `compliance-traceability` | Step 1: Establish Traceability Scope → Step 2: Requirements Definition → Step 3: Design Decisions → Step 4: Implementation → Step 5: Test Coverage → Step 6: Deployment Verification → Step 7: Create the Traceability Matrix → Step 8: Identify Gaps → Step 9: Compliance Sign-Off | Traceability scope; Requirements registry; Design decision registry; Implementation registry; Test evidence registry; Deployment evidence; Traceability matrix; Gap analysis with remediation plan |
| `definition-of-done` | Step 1: Engineer Perspective — Code Quality → Step 2: QA Perspective — Test Coverage and Functionality → Step 3: Security Perspective — Vulnerability Scanning and Review → Step 4: Designer Perspective — Design Fidelity and Accessibility → Step 5: Tech Lead Perspective — Documentation, Maintainability, Deployment → Step 6: Consolidate the DoD Checklist → Step 7: Identify Failing Criteria → Step 8: Make the Done/Not Done Decision | Code quality checklist; Test coverage checklist; Security checklist; Design and accessibility checklist; Documentation and deployment checklist |
| `definition-of-ready` | Step 1: Collect the Work Item → Step 2: PM Perspective — Problem Statement and Acceptance Criteria → Step 3: Architect Perspective — Design Feasibility → Step 4: Security Perspective — Threat Assessment → Step 5: Designer Perspective — UX and Accessibility → Step 6: Tech Lead Perspective — Complexity and Effort → Step 7: Consolidate the DoR Checklist → Step 8: Identify Blocking Issues → Step 9: Communicate Ready/Not Ready | Requirements completeness checklist; Feasibility assessment; Security threat assessment; Design feasibility assessment; Effort and complexity estimate |
| `feature-lifecycle` | Step 1: Establish Feature Context → Step 2: Ideation Phase → Step 3: Requirements Phase → Step 4: Design Phase → Step 5: Development Phase → Step 6: Testing Phase → Step 7: Deployment Phase → Step 8: Operations Phase → Step 9: Closure Phase → Step 10: Document the Feature Lifecycle | — |
| `incident-to-improvement` | Step 1: Postmortem (Engineer Perspective) → Step 2: Root Cause Analysis (QA + Engineer) → Step 3: Security Review (Security Perspective) → Step 4: Process Improvement (Tech Lead) → Step 5: Backlog Items (PM) → Step 6: Consolidate the Incident Report | Postmortem narrative (what happened, when, how resolved); Root cause analysis (the actual causes, not just the symptom); Security impact assessment and remediation steps; Process improvement recommendations with priority and effort; Backlog items with owners, priority, effort estimates |
| `release-checklist` | Step 1: Establish Release Scope → Step 2: PM Sign-Off → Step 3: QA Sign-Off → Step 4: Security Sign-Off → Step 5: Performance Baseline → Step 6: Operations Readiness → Step 7: Deployment Plan → Step 8: Team Readiness → Step 9: Consolidate Release Checklist → Step 10: Make the Release Decision | PM release readiness checklist; QA sign-off with test pass rate, known issues, severity breakdown; Security sign-off with scan results and any exceptions; Performance baseline captured, regression analysis; Operations readiness checklist; Deployment and rollback procedures; Team readiness verification |
| `retrospective-to-action` | Step 1: Frame the Retro → Step 2: Observations (What Happened) → Step 3: Root Cause Analysis → Step 4: Improvement Ideas → Step 5: Prioritize Improvements → Step 6: Assign Owners → Step 7: Consolidate Retro Notes → Step 8: Close the Loop | Retro framing; Observation lists from all team members; Root causes and potential improvements; Improvement ideas with owners and effort estimates; Prioritized improvement list; Assignments |
| `sdlc-phase-gate` | Step 1: Identify Current Phase and Work Item → Step 2: Validate Current Phase Completion → Step 3: Identify Blocking Issues → Step 4: Make the Gate Decision → Step 5: Communicate the Decision | Requirements completeness checklist; Design completeness checklist; Implementation readiness checklist; Testing completeness checklist; Deployment readiness checklist; Operations closure checklist; Blocking issues list with owners and estimates |

### security/application-security

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `api-security-review` | Review Authentication → Review Authorization → Check Rate Limiting & Abuse Prevention → Review Input Validation & Output Encoding → Assess Data Exposure | — |
| `content-security-policy` | Start with Report-Only Mode → Design Base Policy → Allow Trusted External Resources → Secure Inline Scripts & Styles → Monitor & Iterate | — |
| `dast-test-plan` | Scope Definition → Configure DAST Tool → Execute Scan → Analyze Results → Report & Remediate | — |
| `dependency-vulnerability-scan` | Select Scanning Tool → Integrate into Development → Configure Scanning Rules → Remediation Workflow → Monitor & Report | — |
| `penetration-test-scope` | Define Test Objectives → Define Test Scope → Establish Rules of Engagement → Identify Constraints & Limitations → Document Agreements | — |
| `sast-configuration` | Select SAST Tool → Configure Tool → Integrate into Development → Tune for Your Codebase → Measure & Improve | — |
| `security-test-plan` | Define Test Scope → Design Security Test Cases → Implement Automated Tests → Plan Manual Testing → Track & Report Results | — |
| `web-security-headers` | Implement Critical Headers → Implement Additional Headers → Configure Content-Security-Policy (CSP) Properly → Test & Validate Headers → Maintain Headers | — |

### security/compliance-governance

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `audit-preparation` | Establish Audit Timeline & Plan → Organize Documentation & Evidence → Prepare Control Evidence → Coordinate Audit Activities → Manage Post-Audit Remediation | — |
| `compliance-mapping` | Identify Applicable Frameworks → Map Controls to Framework Requirements → Document Control Implementation → Plan Remediation for Gaps → Maintain Mapping Over Time | — |
| `data-classification` | Define Classification Levels → Assign Classification → Define Handling Requirements Per Level → Implement Technical Enforcement → Maintain Classification | — |
| `gdpr-assessment` | Identify Data & Processing Activities → Establish Lawful Basis → Implement Data Subject Rights → Conduct Data Protection Impact Assessment (DPIA) → Incident Response & Regulatory Obligations | — |
| `pci-dss-review` | Understand PCI-DSS Requirements (12 Domains) → Review Network Security (Req 1-4) → Review Systems & Access (Req 5-7) → Review Data Protection (Req 8-10) → Compliance Assessment & Remediation | — |
| `privacy-impact-assessment` | Determine if PIA is Needed → Describe Processing Activity → Identify Privacy Risks → Evaluate Mitigations → Assess Residual Risk & Make Determination | — |
| `security-policy-template` | Define Policy Framework → Structure Each Policy → Develop Core Policies → Enforcement & Governance → Maintain Policies | — |
| `soc2-controls` | Understand Trust Services Criteria (TSC) → Design & Implement Controls for Security (CC) → Design & Implement Controls for Availability (A) → Design & Implement Controls for Processing Integrity (PI) → Prepare for SOC 2 Audit | — |

### security/incident-response

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `containment-strategy` | Isolate Compromised System (Short-term) → Prevent Lateral Movement (Short-term) → Investigation While Contained → Remediation Strategy → Prevent Re-infection & Ongoing Monitoring | — |
| `evidence-preservation` | Identify Evidence to Preserve → Preserve Volatile Data (Before Shutdown) → Preserve Persistent Data (Disk & Logs) → Chain of Custody Documentation → Legal & Admissibility Considerations → Long-term Storage & Retention | — |
| `forensic-analysis-guide` | Evidence Preservation → File System Analysis → Log Analysis → Memory Analysis → Create Forensic Report | — |
| `incident-communication` | Establish Communication Team & Protocols → Internal Communication → Customer Communication → Regulatory Notification → Media & Public Communication → Post-Incident Communication | — |
| `incident-response-plan` | 1. Define Incident Classification & Escalation → 2. Establish the Incident Response Team → 3. Design Detection & Alerting → 4. Containment & Investigation Procedures → 5. Recovery & Communication → 6. Post-Incident Review (Blameless) → 7. Training & Tabletop Exercises | An incident response plan (living document):; ` |
| `lessons-learned` | Prepare for Session → Review Incident Timeline → Analyze Response Activities → Identify Root Causes & Contributing Factors → Generate Action Items → Track & Verify Action Items → Share Lessons Learned | — |
| `recovery-procedures` | Plan Recovery Strategy → Execute Rebuild/Remediation → System Validation → Testing & Validation → Production Resumption → Post-Recovery Verification | — |
| `root-cause-analysis-security` | Understand the Incident Fully → Apply Five Whys Technique → Identify Systemic Issues → Document Findings → Develop Remediation Plan → Implement Preventive Measures | — |

### security/infrastructure-security

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `certificate-management` | Establish Certificate Authority (CA) → Implement HTTPS/TLS → Manage Certificate Lifecycle → Implement Mutual TLS (mTLS) → Code Signing & Artifact Management | — |
| `cloud-security-posture` | Select Assessment Tool → Assess Configuration Against CIS Benchmarks → Execute Automated Scans → Remediation Workflow → Continuous Monitoring | — |
| `container-security-review` | Review Base Images → Implement Image Scanning → Secure Image Build Process → Review Runtime Security → Kubernetes-Specific Security | — |
| `iam-policy-design` | Define Identity Categories → Implement Least-Privilege Access → Design Cloud IAM Policies → Manage Service Account Permissions → Monitor & Audit IAM | — |
| `infrastructure-hardening` | Select & Follow Hardening Baselines → Implement Patch Management → Harden Services → Disable Unnecessary Services & Packages → Implement Security Baselines & Automation | — |
| `kubernetes-security` | Secure API Server Access → Implement RBAC (Role-Based Access Control) → Enforce Pod Security Standards → Implement Network Policies → Secure Secrets & Sensitive Data | — |
| `network-segmentation` | Design Segmentation Model → Implement Segmentation Controls → Define Inter-Segment Communication Rules → Monitor & Enforce Segmentation → Implement Zero-Trust Principles | — |
| `zero-trust-architecture` | Establish Identity Verification → Implement Network Segmentation & Microsegmentation → Enforce Least-Privilege Access → Continuous Monitoring & Anomaly Detection → Encrypt Everything | — |

### security/secure-development

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `authentication-design` | Password Policy → Password Storage → Multi-Factor Authentication (MFA) → Secure Password Reset → Session Management → Credential Transmission | — |
| `authorization-design` | Design Roles & Permissions → Implement Least Privilege → Enforce Authorization Checks → Prevent Common Authorization Bypasses → Audit Authorization Decisions | — |
| `cryptography-selection` | Encryption in Transit → Encryption at Rest → Key Management → Password Hashing → Digital Signatures → Hash Functions | — |
| `input-validation-patterns` | Define Validation Rules → Implement Whitelisting → Canonicalize Before Validation → Validate at Boundaries → Handle Validation Failures Securely | — |
| `output-encoding` | HTML Context → URL Context → JavaScript Context → CSS Context → Use Templating Engines with Auto-Encoding | — |
| `owasp-top-ten-check` | A01: Broken Access Control → A02: Cryptographic Failures → A03: Injection → A04: Insecure Design → A05: Security Misconfiguration → A06: Vulnerable Components → A07: Authentication Failures → A08: Software & Data Integrity Failures → A09: Logging & Monitoring Failures → A10: SSRF (Server-Side Request Forgery) | — |
| `secrets-management` | Never Hardcode Secrets → Use Secure Vault → Environment Variables → Access Control → Key Rotation → Secrets in Logs → Certificate Management | — |
| `secure-coding-review` | 1. Identify Privileged Code Paths → 2. Check for OWASP Top 10 Vulnerabilities → 3. Validate Input Handling → 4. Review Authentication & Authorization → 5. Check Cryptography → 6. Review Error Handling & Logging | A security review comment:; `markdown |
| `session-management` | Session Token Generation → Cookie Configuration → JWT Token Configuration → Session Invalidation → Session Fixation Prevention → Concurrent Session Limits | — |

### security/security-operations

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `alert-triage` | Establish Alert Categories → Triage Questions → Classify Alert Outcome → Document Triage Decision → Escalation Process → Feedback & Rule Improvement | — |
| `detection-engineering` | Threat Modeling → Map Attacks to MITRE ATT&CK → Develop Detection Hypotheses → Assess Detection Capability → Build & Test Detections → Measure & Improve | — |
| `log-analysis-security` | Understand Log Sources & Fields → Reconstruct Attack Timeline → Analyze Specific Attack Scenarios → Use Log Analysis Tools → Correlation & Pattern Detection → Generate Findings & Recommendations | — |
| `security-monitoring-strategy` | Define Monitoring Scope → Select Monitoring Tools → Define Detection Capabilities → Establish Alert Tuning Process → Implement Operational Processes → Plan for Resilience | — |
| `siem-rule-design` | Understand Attack Patterns → Design Rules for Common Attacks → Implement Detection Correlation → Tune Rules for Accuracy → Implement Alerts & Escalation → Monitor Rule Effectiveness | — |
| `threat-intelligence-integration` | Establish Threat Intelligence Program → Integrate Indicators into Operations → Develop TTPs-Based Detections → Execute Threat Hunting → Threat Reporting & Communication → Measure Effectiveness | — |
| `vulnerability-management-program` | Scanning & Discovery → Establish Prioritization Framework → Remediation Planning & Execution → Vulnerability Tracking & Metrics → False Positive Management → Establish Governance | — |

### security/security-toolkit

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `bug-bounty-program` | Define Program Scope & Rules → Establish Reward Structure → Recruitment & Engagement → Submission & Triage Process → Remediation & Payment → Program Metrics & Improvement | — |
| `red-team-exercise` | Plan Red Team Exercise → Red Team Preparation → Execute Exercise → Monitoring & Observation → Post-Exercise Review (Hot-Wash) → Implementation & Metrics | — |
| `secure-architecture-review` | Understand System Architecture → Review Security Properties → Assess Threat Resilience → Review Compliance & Operational Readiness → Identify Risks & Recommendations → Review Report & Follow-up | — |
| `security-awareness-training` | Assess Training Needs → Develop Training Content → Select Delivery Method → Implement & Schedule → Measure & Improve → Build Positive Security Culture | — |
| `security-champion-program` | Establish Program Structure → Training Champions → Engagement & Support → Drive Security Improvements → Recognition & Incentives → Measure Program Success | — |
| `security-documentation` | Define Documentation Framework → Develop Quality Standards → Documentation Content → Organization & Accessibility → Maintenance & Updates → Effectiveness | — |
| `security-metrics-dashboard` | Select Key Metrics → Design Dashboards for Audience → Visualize Data Effectively → Establish Baselines & Targets → Report & Communicate → Improve Dashboard Iteratively | — |

### security/threat-modeling

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `abuse-case-design` | Enumerate Use Cases First → For Each Use Case, Ask Abuse Questions → Document Abuse Cases in Standard Format → Map to Controls → Prioritize | — |
| `asset-inventory` | Enumerate All Assets → Classify Each Asset → Document Dependencies → Assign Financial Value → Map to Controls | — |
| `attack-tree-modeling` | Define Root Goal → Decompose Recursively → Assign Attributes to Leaf Nodes → Propagate Metrics Upward → Visualize & Prioritize | — |
| `data-flow-diagram-security` | Identify System Boundary → Decompose Major Processes → Annotate Trust Boundaries → Classify Data Flows → Identify Storage → Review for STRIDE | — |
| `risk-scoring` | Define Scoring Scale → Alternatively, Define Quantitative Scoring → For Each Threat, Assess Likelihood → Assess Impact → Calculate Risk Score and Prioritize → Document Risk Decisions | — |
| `stride-analysis` | 1. Map Components & Data Flows → 2. For Each Component, Apply STRIDE → 3. Document Threats → 4. Assign Severity → 5. Link to Mitigations → 6. Review & Prioritize | A STRIDE Threat Model document:; ` |
| `threat-identification` | Profile the Attacker → Reference MITRE ATT&CK → Cross-Reference CWE/CVE → Add Industry Threats → Document Attack Chains → Connect to STRIDE & Assets | — |
| `threat-library` | Define Threat Taxonomy → Create Threat Templates → Populate Library from Multiple Sources → Tailor to Your Stack → Maintain the Library | — |
| `trust-boundary-analysis` | Map Trust Zones → Identify Boundaries → For Each Boundary, Document → Assess Threats at Boundaries → Design Controls | — |

### tech-lead/code-review-leadership

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `automated-review-setup` | Choose core tools by language → Configure autofix → Add PR automation → Set up for local development → Don't over-instrument → Measure tool accuracy | — |
| `code-review-standards` | 1. Define Review Scope → 2. Create the Review Acceptance Checklist → 3. Clarify Nits vs. Blockers → 4. Set Expectations on Time & Process → 5. Define Who Can Approve → 6. Create Examples & Guidance → 7. Establish Escalation Path → 8. Document Exceptions & Special Cases | A code review standards document:; ` |
| `constructive-feedback` | Frame feedback as questions → Separate must-haves from nice-to-haves → Provide examples → Learn in public → Celebrate good work → Know your team → Offer to pair → Model the feedback you want | — |
| `merge-strategy` | Assess team workflow → Choose strategy → Document in CONTRIBUTING.md → Enforce in CI/CD → Set commit message standards → Consider exceptions | — |
| `quality-gate-definition` | Define gate categories → For each gate, set thresholds → Create bypass criteria → Test the gates → Make gates visible → Measure false positives | — |
| `review-checklist-design` | Identify defect categories → For each category, write one checklist item → Add failure examples → Separate automation from judgment → Keep to 5-8 items → Link to standards → Iterate annually | — |
| `review-culture-guide` | Model good review behavior → Celebrate reviews → Celebrate learning from review → Make review a learning opportunity → Establish "review as gift" framing → Normalize back-and-forth discussion → Create safe space for "I don't understand" → Measure culture health | — |
| `review-metrics` | Track lead time → Track review participation → Track review cycle time → Track reviewer diversity → Track comment count → Track defect escape → Correlate to outcomes | — |

### tech-lead/cross-functional-leadership

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `alignment-facilitation` | Set clear session goal → Include right people → Structure the session → Make decision explicitly → Write it down | — |
| `cross-team-coordination` | Create shared roadmap → Dependency mapping meetings → Shared architecture documents → Weekly async status → Escalation path | — |
| `design-engineering-handoff` | Include engineer early → Document assumptions → Create spec templates → Leave room for engineering optimization → Feedback loops | — |
| `scope-negotiation` | Establish constraints upfront → Break features into priority tiers → Use time boxing → Offer alternatives → Document decisions | — |
| `stakeholder-communication` | Know your audience → Translate, don't dumb down → Use comparisons → Quantify tradeoffs → Calibrate confidence | — |
| `technical-product-partnership` | Establish shared metrics → Visibility into technical roadmap → Educate on tradeoffs → Create decision frameworks → Regular alignment meetings | — |
| `technical-requirements-translation` | Clarify the business outcome → Quantify constraints → List assumptions → Discover hard parts → Create decision tree | — |

### tech-lead/engineering-excellence

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `accessibility-standards` | Know WCAG standards → Checklist per level → Integrate into workflow → Involve people with disabilities → Measure and track | — |
| `coding-standards` | Adopt existing standards → Automate enforcement → Document rationale for custom rules → Grandfather existing code → Gather feedback, iterate | — |
| `developer-experience-audit` | Design audit framework → Track baseline → Gather qualitative feedback → Identify top frictions → Plan improvements and remeasure | — |
| `documentation-standards` | Establish documentation zones → Create doc template → Assign owners → Link from code → Track doc usage | — |
| `monitoring-strategy` | Define SLOs (Service Level Objectives) → Choose metrics → Set alert thresholds carefully → Alert on trends, not absolutes → Invest in runbooks | — |
| `security-practices` | Threat model critical systems → Establish secrets management → Implement least privilege → Automate security checking → Incident response plan | — |
| `testing-strategy` | Define pyramid → Establish quality gates → Eliminate flakiness aggressively → Track test metrics → Rotate test maintenance | — |
| `tooling-strategy` | Audit current tooling → Identify gaps → Prioritize by leverage → Plan adoption → Measure and iterate | — |

### tech-lead/process-engineering

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `branching-strategy` | Choose strategy based on product model → Define branch naming convention → Set merge requirements → Define long-running branch policy → Communicate and enforce | — |
| `change-management` | Classify changes by risk → Create change template → Define change windows → Establish communication protocol → Monitor after change | — |
| `definition-of-ready` | Define DoR checklist → Triage new work → Train on DoR → Enforce gently → Update DoR based on pain | — |
| `development-workflow` | Map current workflow → Identify bottlenecks → Design with constraints in mind → Set targets → Iterate based on data | — |
| `incident-management-process` | Define severity levels → Establish incident roles → Create runbook templates → Design postmortem process → Track and improve | — |
| `on-call-rotation` | Choose rotation schedule → Define on-call responsibilities → Minimize disruption → Plan handoff process → Track and measure | — |
| `process-improvement` | Capture process friction → Measure the pain → Diagnose root cause → Run small experiments → Implement, measure, iterate | — |
| `release-management` | Define release cadence → Create release checklist → Design deployment pipeline → Plan rollback → Communicate and coordinate | — |

### tech-lead/team-development

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `career-ladder-design` | Define ladder tracks → Document level expectations → Establish clear criteria → Create advancement rubric → Include examples and compensation bands | — |
| `knowledge-sharing-plan` | Map critical knowledge → Choose distribution methods → Build accountability into process → Create documentation standards → Measure and iterate | — |
| `mentoring-plan` | Establish relationship foundation → Define skill development priorities → Design learning experiences → Establish feedback rhythm → Track measurable outcomes | — |
| `onboarding-program` | Design phase 1 (Days 1-5): Integration and context → Design phase 2 (Week 2-3): Shallow contributions → Design phase 3 (Week 4-6): Guided projects → Design phase 4 (Week 7-12): Independent work and integration → Measure and iterate | — |
| `one-on-one-template` | 1. Set the Rhythm → 2. Create Psychological Safety → 3. Start with Them (They Drive the Agenda) → 4. Surface Concerns Gently → 5. Discuss Growth (Every 1:1) → 6. Offer Your Perspective (Last 5-10 min) → 7. Be Human → 8. Document Outcomes | — |
| `pair-programming-facilitation` | Choose pairing scenarios strategically → Set explicit roles and cadence → Establish psychological safety → Create feedback loops in the session → Document learnings asynchronously | — |
| `performance-feedback` | Prepare the conversation → Use SBI structure for observations → Show you believe in them → Make it actionable → Follow up | — |
| `skill-matrix` | Define skill domains → Establish proficiency scale → Map current team → Compare against role levels → Create development roadmap | — |

### tech-lead/tech-lead-toolkit

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `engineering-blog-post` | Pick worthy topic → Structure clearly → Include technical depth and context → Write accessible → Get feedback before publishing | — |
| `hiring-interview-design` | Define what you're assessing → Design assessments per dimension → Create rubric → Standardize questions and structure → Diverse interview panel | — |
| `retrospective-facilitation-tl` | Set psychological safety tone → Run structured format → Surface real issues → Pick 2-3 actions max → Close with commitment | — |
| `team-charter` | Define team purpose → Articulate values → Establish norms → Define decision-making → Review annually | — |
| `team-health-check` | Design health survey → Administer anonymously → Synthesize findings → Share and plan actions → Recheck in 3-4 months | — |
| `tech-lead-journal` | Create template → Document decisions → Track team patterns → Reflect on effectiveness → Review quarterly | — |
| `tech-talk-preparation` | Choose topic strategically → Create outline, not script → Practice out loud, multiple times → Design slides for legibility → Prepare for Q&A | — |

### tech-lead/technical-decision-making

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `build-vs-buy-analysis` | Define decision criteria matrix → Score build option → Score buy option → Quantify differentiation → Document decision and review trigger | — |
| `decision-matrix` | List options → Define criteria → Score each option → Calculate weighted score → Document tradeoffs | — |
| `post-decision-review` | Schedule review 3-6 months after decision goes live → Compare outcome to prediction → Assess decision quality, not outcome luck → Identify surprises and new learnings → Extract decision rules for next time | — |
| `proof-of-concept-criteria` | Define PoC trigger criteria → Scope PoC narrowly → Define success criteria upfront → Timeline and effort → Go/no-go decision process | — |
| `rfc-process` | Define RFC scope → Create template → Set comment period → Facilitate discussion → Document decision | — |
| `risk-mitigation-plan` | List risks → Assess risk severity → Plan mitigation per risk → Define monitoring triggers → Document and communicate | — |
| `spike-plan` | Define the spike question → Set explicit boundaries → Design learning experiments → Run experiments rapidly → Document findings and decision | — |
| `technology-evaluation` | Define evaluation criteria → Research systematically → Create comparison table → Document tradeoffs explicitly → Include reversibility in evaluation | — |

### tech-lead/technical-planning

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `capacity-planning` | Baseline current capacity → Model quarterly scenarios → Account for ramp time → Model attrition risk → Add contingency → Map to roadmap items → Make staffing cases | — |
| `dependency-mapping` | List all work items → For each item, ask → Classify dependencies → Build the graph → Find the critical path → Identify parallelization → Plan handoff points → Build contingency plans | — |
| `estimation-techniques` | Choose the horizon → For story points → For t-shirt sizes → For planning poker → Build a team estimate profile → Account for unknowns → Decompose aggressively | — |
| `risk-register` | Brain dump risks → For each risk, estimate probability and impact → Calculate priority → Define trigger conditions → Design mitigation → Assign owners → Review quarterly | — |
| `sprint-planning-guide` | Calculate available capacity → Prioritize ruthlessly → Estimate from the backlog → Identify dependencies and risks → Build the sprint goal → Confirm commitment → Document assumptions | — |
| `technical-debt-prioritization` | Create a debt inventory → For each debt item, estimate impact on velocity → Estimate cost to pay down → Calculate payoff ROI → Prioritize by impact and payoff → Build into roadmap → Measure before and after | — |
| `technical-roadmap` | 1. Gather Inputs → 2. Define Themes (3-5 Strategic Areas) → 3. Map Initiatives Within Each Theme → 4. Establish Quarterly Milestones → 5. Build the Narrative | A roadmap document (shared with engineering and stakeholders):; ` |
| `velocity-analysis` | Gather historical data → Calculate average and standard deviation → Chart the trend → Stratify by sprint type → Identify bottlenecks → Forecast with confidence bands → Set realistic commitments → Measure impact of process changes | — |
| `work-breakdown-structure` | Start with the initiative → Identify work streams → For each work stream, list epics → For each epic, estimate scope → Identify critical dependencies → Assign ownership → Define done criteria | — |

## Power BI Analyst Skill

_1 skills._

### powerbi-analyst-skill-main

| Skill | Workflow steps (modes) | Outputs |
| --- | --- | --- |
| `powerbi-analyst` | Study the data → Engineer Power Query (M) → Build relationships → Create measures → Plan visuals → Governance + validate | 1. Dataset Study & Column Classification (produced first); 2. One .md file of Power Query M code per table; 3. relationships.tmdl.md; 4. measures.tmdl.md; 5. Visualization Blueprint (step-by-step, actionable); 6. Data Quality & Governance Notes (only what is relevant); 7. Assumptions & Data Study Justifications — explain WHY each choice was made,; and why available techniques were deliberately skipped |

