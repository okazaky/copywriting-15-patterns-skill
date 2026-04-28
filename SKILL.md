---
name: copywriting-15-patterns
description: >-
  Generate Japanese catchphrases, titles, hooks, and headings using a
  15-pattern, 5-cluster framework for copywriting.
  Use when asked to write a キャッチコピー, タイトル案, 見出し, 冒頭フック, X投稿の出だし,
  or when the user refers to 禁忌ゲート, 数値アンカー, 反転トリガー, 感情ドライブ,
  音感ワード, 二人称コール, 内側開示, 検証ナラティブ, 時限プレッシャー, 物語の入口.
---

# Copywriting 15 Patterns / 5 Clusters

Use this skill to turn a bland Japanese headline request into multiple stronger options.
The 15 hooks are organised into 5 functional clusters so you can pick by job-to-be-done.

## 5 Clusters × 3 Patterns

### A. Curiosity Gates — to stop the scroll
- 01: 禁忌ゲート (Forbidden Gate)
- 04: 反転トリガー (Reversal Trigger)
- 10: 内側開示 (Inside Reveal)

### B. Specificity — to add credibility
- 02: 数値アンカー (Numeric Anchor)
- 09: 対比軸 (Contrast Axis)
- 14: 検証ナラティブ (Verification Narrative)

### C. Emotional Hooks — to raise body temperature
- 05: 感情ドライブ (Emotional Drive)
- 12: 音感ワード (Sonic Word)
- 13: 等身大宣言 (Equal-Footing Declaration)

### D. Reader Anchoring — to make it personal
- 03: 自己投影クエスチョン (Self-Reflection Question)
- 07: 宛名ロック (Audience Lock)
- 15: 二人称コール (Second-Person Call)

### E. Narrative Push — to drive movement
- 06: 物語の入口 (Narrative Entry)
- 08: 落とし穴開示 (Pitfall Disclosure)
- 11: 時限プレッシャー (Time Pressure)

## What To Load

- If the user names a pattern, cluster, or number, open the matching `references/pattern-XX-*.md`.
- If the user asks broadly for title ideas or catchphrases, start with one pattern from each of A〜D (e.g. `01`, `02`, `05`, `15`).
- Add more patterns one by one instead of loading all 15 at once.

## Workflow

1. Identify the asset: title / catchphrase / heading / X hook / CTA.
2. Identify the target: who it is for, what benefit/fear/desire/curiosity to trigger.
3. Pick 3〜5 patterns from at least 2 clusters (so the options have real variance).
4. Produce multiple options grouped by pattern.
5. Keep outputs concise and natural Japanese. Avoid translation-flavoured wording.

## Output Style

- Default to 10 options unless the user asks for a different count.
- Group by pattern when useful.
- Keep each line standalone and usable as-is.
- If the user provides a draft, improve it rather than rewriting from zero.
- When asked for one best version, return:
  - best option
  - short why
  - 2 backup options

## Cluster Selection Guide

- Conversion or urgency → Cluster E (`08`, `11`) + Cluster D (`15`)
- Credibility or proof → Cluster B (`02`, `09`, `14`)
- Stop-the-scroll → Cluster A (`01`, `04`, `10`)
- Empathy & resonance → Cluster C (`05`, `13`) + Cluster D (`03`)
- Persona-targeted offers → Cluster D (`07`) + Cluster A (`01`)

## Constraints

- Do not fabricate factual numbers unless the user provided them.
- Avoid manipulative or deceptive claims; no fake deadlines or invented data.
- Avoid spammy repetition and excessive punctuation unless explicitly requested.
