---
name: define-selected-word
description: Explain the meaning of a selected, highlighted, quoted, or otherwise indicated word or short phrase. Use when the user asks what a selected word means, asks to define a highlighted term, asks for a plain-language meaning, pronunciation, part of speech, example sentence, or context-specific explanation of a word in surrounding text.
---

# Define Selected Word

## Response Workflow

1. Identify the selected term from the user message or surrounding context. Treat quoted text, highlighted text, a single word after "define", or the only obvious term in the prompt as the selection.
2. If no selected word is visible, ask the user to provide the word or paste the sentence containing it.
3. If context is available, explain the meaning that best fits that context first. Mention other common meanings only when they are likely to matter.
4. Keep the answer concise and friendly:
   - Term
   - Part of speech, when useful
   - Plain-language meaning
   - Example sentence
   - Context note, if the surrounding sentence changes the meaning
5. For non-English words, identify the language if clear, give the English meaning, and include a natural usage note when helpful.
6. For slang, technical, legal, medical, financial, or newly popular terms, say when the meaning is domain-specific. Use current sources if the meaning may have changed recently or depends on up-to-date usage.

## Style

Use simple wording before dictionary-style precision. Prefer "It means..." over long lexical entries. Avoid overwhelming the user with etymology, rare senses, or exhaustive synonym lists unless they ask for them.

## Examples

Selected word: "resilient"

Response shape:
`Resilient` means able to recover after difficulty or stress. It is usually an adjective. Example: "The team stayed resilient after the setback."

Selected phrase: "bear market"

Response shape:
`Bear market` means a period when investment prices are generally falling, especially by 20% or more from recent highs. In finance context, it suggests pessimism and caution among investors.
