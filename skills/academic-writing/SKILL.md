---
name: academic-writing
description: Rules for writing and revising English academic papers (ML/CS style) and their figures. Use when drafting or editing paper sections, experiment analysis, captions, cross-references, or plotting figures for a paper.
---

# Academic Writing

Rules 1–7 apply to text you write and figures you make. Rule 8 governs how you revise text the author already wrote.

## 1. Every sentence advances the argument

Test each sentence: if it were deleted, would the reader lose a fact, a finding, or a reasoning step? If not, delete it.

Delete defensive sentences:

- Pre-emptive concessions that do not change the conclusion ("Although our sample is limited, …").
- Denials of claims nobody made ("This does not imply that …").
- Justifications of the setup ("To ensure a fair comparison, …"). State the setup directly.
- Empty emphasis ("It is worth noting that …", "Importantly, …").

Keep qualifiers the reader needs to interpret a result, such as a counting rule or a result that holds only on a subset. Put limitations in the Limitations section.

## 2. Plain word choice

- Use one term per concept throughout the paper. Do not switch to synonyms for variety.
- Define each term at its first occurrence and use exactly that term afterwards.
- Prefer common academic words: use, show, improve, compare, limit, provide. More formal words are fine when they are common in papers and instantly readable: demonstrate, indicate, substantially, consistently.
- Avoid deliberate or rhetorical words: leverage, utilize, underscore, shed light on, delve into, showcase, mirror.
- No colloquialisms (a lot of, pretty, basically, get, kind of). No contractions (don't, it's).
- Prefer verbs to noun stacks and needless passives. Write "the model fails to …". Avoid "a failure of the model in … is observed".

## 3. Avoid AI-typical punctuation and patterns

- Use few semicolons and dashes (including `---` and `--` in LaTeX). Split the sentence, or use a comma or parentheses.
- Avoid "rather than", "instead of", and contrast templates such as "A is X, not Y". State directly what A is. Mention Y only when the contrast itself is the point, and then in its own plain sentence.

## 4. Experiment analysis: findings, with the key numbers

- Figures and tables give the full numbers. The text explains what they show.
- Open each paragraph with its conclusion, then give the comparison or reason that supports it.
- State the important, informative numbers directly and exactly ("keeps 11% of its score", "1.7 to 4.0 times as many turns"). Do not avoid key metrics, and do not force them into vague approximations such as "about two thirds" or "about half".
- Use relative wording ("drops sharply", "increases with X", "varies widely across models") for trends, and for numbers that would only repeat a table cell.
- Never restate a table cell by cell or turn a figure into prose.
- After writing, check every number. Keep it if it carries a finding. If it only repeats the table, delete it or turn it into a trend.

## 5. Cross-references the reader needs

- Reference each figure or table once, at its first discussion.
- Reference another section or appendix only when the reader must jump there to follow the current text. Drop "see … for details" where possible.
- Refer by content when possible: "the ablation study" reads better than "Section 5.3".
- Roadmap sentences (e.g., at the end of the introduction) may reference each section by number.

## 6. Short captions

A caption is a bold title phrase plus at most one sentence with information the reader cannot get from the figure itself, such as a counting rule.

Leave out:

- Encodings (what colors, line styles, or abbreviations mean). The legend already shows them.
- Data-scope details (task counts, run counts, subsets) unless the reader must know them.
- Layout descriptions ("top shows …, bottom …", "(a) X versus Y").

## 7. Figure design

A figure should show its content clearly, so the reader quickly sees the important phenomenon, result, trend, or conclusion.

- Use at most two fonts in a figure.
- Remove small-text annotations that carry no meaning. Every piece of text in a figure must help the reader grasp its main point.

## 8. Revising the author's existing text

- Change as little as possible. Keep the author's line of argument, evaluative words, and transitions ("To bridge this gap", "Furthermore").
- Fix only what is clearly wrong: noun stacks, opaque jargon, factual errors.
- Do not delete sentences, swap claims, or restructure paragraphs on your own. When you see such a problem, including violations of rules 1–7, point it out and let the author decide.
