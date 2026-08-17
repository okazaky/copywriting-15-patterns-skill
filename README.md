# copywriting-15-patterns

A Claude Code skill that turns a bland Japanese headline request into multiple stronger options using 15 copywriting hooks organised into 5 functional clusters.

日本語のキャッチコピー・タイトル・見出し・X投稿の冒頭フックを、5クラスター × 3パターンの計15型から自動生成する Claude Code skill です。

## Inspiration / インスパイア元

The decision to package Japanese copywriting hooks as a single agent-side skill was inspired by tetumemo's Manus Agent Skills article, which itself reflects the long-running Japanese sales copywriting tradition (大橋一慶『セールスコピー大全』『ポチらせる文章術』ほか).

- tetumemo: https://tetumemo.m-newsletter.com/posts/735deaf9bb7782c8
- Reference: 大橋一慶 / 株式会社みんなのコピー (https://copymarketing.net/)

This skill is **not a port** of either work. The pattern names, clustering structure, internal explanations, prompt templates, and example shapes are independently authored for this repository. See [CREDITS.md](./CREDITS.md) for details and how to request changes.

## Install

### Claude Code (manual)

```bash
git clone https://github.com/okazaky/copywriting-15-patterns-skill.git ~/.claude/skills/copywriting-15-patterns
```

Restart your Claude Code session. The skill activates when you ask for キャッチコピー / タイトル案 / 見出し / X投稿の冒頭フック / CTA.

### Plugin install (planned)

```bash
claude plugin install copywriting-15-patterns
```

## Usage

```
> 「無在庫物販スクール」のLPの見出しを10案ください
```

The skill picks 3-5 patterns from at least 2 clusters, and produces grouped options.

You can also invoke a specific pattern or cluster by number or name:

```
> パターン04（反転トリガー）でX投稿の冒頭フックを5案
> Cluster A の3パターンで見出しをそれぞれ3案ずつ
```

## 5 Clusters × 3 Patterns

### A. Curiosity Gates — to stop the scroll
| # | Pattern |
|---|---------|
| 01 | 禁忌ゲート (Forbidden Gate) |
| 04 | 反転トリガー (Reversal Trigger) |
| 10 | 内側開示 (Inside Reveal) |

### B. Specificity — to add credibility
| # | Pattern |
|---|---------|
| 02 | 数値アンカー (Numeric Anchor) |
| 09 | 対比軸 (Contrast Axis) |
| 14 | 検証ナラティブ (Verification Narrative) |

### C. Emotional Hooks — to raise body temperature
| # | Pattern |
|---|---------|
| 05 | 感情ドライブ (Emotional Drive) |
| 12 | 音感ワード (Sonic Word) |
| 13 | 等身大宣言 (Equal-Footing Declaration) |

### D. Reader Anchoring — to make it personal
| # | Pattern |
|---|---------|
| 03 | 自己投影クエスチョン (Self-Reflection Question) |
| 07 | 宛名ロック (Audience Lock) |
| 15 | 二人称コール (Second-Person Call) |

### E. Narrative Push — to drive movement
| # | Pattern |
|---|---------|
| 06 | 物語の入口 (Narrative Entry) |
| 08 | 落とし穴開示 (Pitfall Disclosure) |
| 11 | 時限プレッシャー (Time Pressure) |

## Constraints

- Numbers are not fabricated unless provided by the user.
- Manipulative or deceptive claims are avoided. No fake deadlines or invented data.
- Default output is 10 options unless the user asks otherwise.

## License

MIT — see [LICENSE](./LICENSE).

The MIT licence applies to all original content in this repository (pattern names, clustering, explanations, prompt templates, example shapes, README/SKILL.md/CREDITS). General concepts behind individual hooks (using numbers, asking questions, naming the audience, etc.) are widely shared across copywriting literature; this skill makes no claim of originality over those concepts.

## Acknowledgements

- **tetumemo** — for the inspiration of bundling Japanese copywriting hooks into a single agent skill (Manus Agent Skills).
- **大橋一慶 / 株式会社みんなのコピー** — for the long-running Japanese sales copywriting framework that informs much of the field.

If either party prefers a different acknowledgement style, or removal, please open an issue.
