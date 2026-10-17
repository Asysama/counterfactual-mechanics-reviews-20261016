# Generator review — PR #702

Decision: NOT VERIFIED
Generator correctness: PASS
Reviewed exact head: a9a5fbe3a08a2b74109c4b642730a6bc4064fb85
Generator: center_of_percussion_support_impulse_creation
Runtime provenance scope: NEW; status PASS.
Declared target: 100000 accepted cases. Smaller-target rationale: not applicable.
Declared-target scale readiness: PASS. Static-only audit PASS does not mean 100000 rendered cases.
Production readiness: NOT READY for final submission pending hosted browser playback and seeking.

## Blocking findings

Native full-clip visual review passed. Hosted browser playback and seeking could not be observed because the browser connection is unavailable. Do not submit.

## Six hard gates

| Gate | Result | Evidence |
|---|---|---|
| Output contract | PASS | 2 complete native cases; 8 native streams; 2048² / 24 fps / 120 frames / 5s |
| Violating-object-only mask | PASS | 120-frame binary RGB and red-overlay checks; separately selected geometry identity pass; no shadows |
| Real scaling | PASS | 100000 distinct accepted static profiles; six controlled rendered axes; two visually different formal cases; 16 physical-axis corners |
| Official unpatched environment | PASS | Clean source; official pinned bpy 4.5.3; actual Python, renderer, GPU/driver, encoder and dependency witness |
| Decoded matched control | PASS | Exact decoded True/CF prefix and matching camera; first divergence and evidence bound to frames |
| Semantic consistency | PASS | Independent mechanics; standalone prompts; single registered operator; full-clip visual review passed; hosted UI playback pending |

## Behavioral and semantic review

Resolved presentation findings: removed all scene text objects and unsupported schematic datum markers; spring gauges have solid mounting necks. Physical ruler ticks, attached needles and painted rod marks remain. These scene corrections do not alter the motion equations or per-frame state.

正常碰撞瞬间支点不受冲击；反事实支点突然横向跳动。后续平滑移动是正常响应。

Title, README, registered operator, metadata, independent mechanics and the two standalone prompts describe the same contrast. True completes the normal outcome; CF changes exactly one rule. Source setup, nuisance appearance and camera are matched. Visual review of connection continuity, silhouette quality, event completion, observation tail and final visibility: PASS. No engine-native physics claim.

## Timebase

One video second equals one physical second. Recorded step is 1/24 s. Internal solver steps are explicitly separate. Both branches share the time mapping; native clips last 5 seconds.

## Runtime and exact-version binding

Source PR: https://github.com/hipo-dev/counterfactual-data/pull/702

The retained successful-render witness binds clean commit a9a5fbe3a08a2b74109c4b642730a6bc4064fb85, seeds42/98, actual command, pinned official package environment, GPU/driver, renderer and encoder to artifact SHA256 values. Each accepted case maps to exactly one witness. Both native videos and separate browser derivatives have checksums. No historical partial evidence is used.

## Scale readiness and production

100000 processed/static accepted profiles, 100000 unique effective signatures and all six axis buckets covered; disjoint eight-shard audit. Six rendered low/high controlled perturbations plus baseline; native seeds42 and98 differ across multiple physical and nuisance details. Sixteen combined physical-axis corners independently checked without rendering. Two complete rendered cases are the Sara workflow default. No 40-case or 100000-rendered batch claim. Production resume verifies source, dependencies, configuration and manifests; incompatible resume fails closed. No seed replacement or missing accepted quota.

## Reproduction and retained artifacts

Seed42 was rerendered from its recipe in the exact official environment, with a separate runtime witness. All four streams were compared; frame counts and mask equality are mandatory, RGB mean tolerance <0.1/255 and maximum frame mean <0.5/255. Actual measurements are in evidence/reproduce-compare.json.

## Client-facing and independent review

Masks display white foreground on black; overlays replace only target mask pixels with pure red. All native 120-frame streams are independently decoded. The target identity pass uses an explicit reviewer-selected name set and checks projected visibility. Hosted playback/seek, full-clip review, anonymous URLs and backup verification: NOT VERIFIED. Browser derivatives are 1024 pixels and are never used as authoritative native-mask evidence.

## Accepted case inventory

[
  {
    "case_id": "center_of_percussion_support_impulse_creation_00000042",
    "intervention": 23,
    "first_changed": 24,
    "evidence": 27
  },
  {
    "case_id": "center_of_percussion_support_impulse_creation_00000098",
    "intervention": 27,
    "first_changed": 28,
    "evidence": 30
  }
]

## Delivery status

Contributor self-check only. User review pending. No Sara form opened, filled or submitted. Review URL: https://asysama.github.io/counterfactual-mechanics-reviews-20261016/center_of_percussion_support_impulse_creation/a9a5fbe3a08a2b74109c4b642730a6bc4064fb85/index.html

## Remaining delivery check

Overall decision remains NOT VERIFIED and self_check_complete=false. Anonymous HTTP and complete browser-file decoding passed; these do not substitute for actually observing hosted browser playback and seeking. User review remains pending and Sara has not been contacted.
