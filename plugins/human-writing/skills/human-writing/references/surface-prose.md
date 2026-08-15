# Surface prose

Use this as a positive revision pass. Change only what improves the task and preserves its content contract.

| Pattern | Revision target |
| --- | --- |
| Buried point | Lead with the actual point |
| Abstract claim | Use supplied concrete detail |
| Inflated significance | State the proportionate claim |
| Promotional language | Describe observable value |
| Mechanical symmetry | Let structure follow meaning |
| Uniform cadence | Vary rhythm by emphasis |
| Fake intimacy or signposting | Begin the content directly |
| Generic conclusion | End on the last useful fact or earned image |
| Vague authority | Name the supplied source or remove the attribution |
| Unsupported specificity | Retain the source's uncertainty |
| Chatbot residue | Remove offers, acknowledgements, and process narration |
| Voice flattening | Preserve defensible quirks from the user's sample |

## Promotional rewrite output contract

Classify each source clause and benefit phrase before rewriting:

1. **Observable function:** what the product does or combines.
2. **Concrete consequence:** a modest change in a user's action or workflow that the source is specific enough to state without inference.
3. **Non-factual framing:** promotional self-evaluation, including importance, novelty, category, or future positioning. Framing has no output slot.

Build the output from filled slots:

1. Fill each function slot with the observable action and concrete objects supplied by the source.
2. Fill one consequence slot for each distinct consequence the source names concretely; state it plainly and proportionately.
3. Treat a cluster of abstract benefits as one candidate consequence slot. Fill it only when source information makes the consequence concrete without inference; otherwise leave the slot empty and retain the function.
4. Group compatible function slots into one sentence; use separate sentences for distinct functions.
5. Stop after the last filled slot. If the source supplies one function and no qualifying consequence, return one function sentence.

Final gate:

1. Split each draft sentence into its clauses and each benefit phrase in a series.
2. Map every unit separately to a filled function or consequence slot.
3. Retain a sentence only when every unit maps. Remove unmapped units, then repeat the gate.

## Avoid false positives

Preserve terminology, deliberate repetition, useful headings and lists, passive voice where the actor is unknown or irrelevant, and punctuation patterns established by the user's sample. Do not treat a single em dash, transition, formal word, or polished sentence as evidence of AI authorship.
