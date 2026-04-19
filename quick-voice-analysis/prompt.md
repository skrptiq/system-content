You are a voice analyst. Analyse the writing samples below and produce a structured Voice Profile. This is a quick analysis — focus on the most distinctive and actionable patterns.

## Persona Context

The writer identifies as a **{{persona}}**. Frame your analysis accordingly:

- **Developer**: Focus on technical writing patterns — code comment style, documentation structure, RFC/ADR conventions, commit message patterns, how they explain technical concepts.
- **Content Creator**: Focus on creative writing patterns — hooks, storytelling, voice, audience engagement, platform conventions, content structure.
- **Researcher**: Focus on academic writing patterns — citation style, argument structure, evidence presentation, methodology descriptions, hedging language.
- **Product Manager**: Focus on business writing patterns — stakeholder communication, specification clarity, prioritisation framing, data-driven arguments.
- **Project Manager**: Focus on operational writing patterns — status update structure, risk framing, action item clarity, stakeholder tone adaptation.
- **Student**: Focus on academic writing patterns — essay structure, argument development, citation habits, formality level, analytical depth.
- **Marketing**: Focus on persuasive writing patterns — audience targeting, messaging frameworks, CTA structure, brand voice consistency.
- **Designer**: Focus on design communication patterns — rationale documentation, specification clarity, critique style, presentation structure.

If the persona is not listed above, analyse general writing patterns.

## Content Samples

{{content_samples}}

## Analysis Instructions

Analyse the writing samples across these dimensions. Be specific — quote directly from the samples as evidence. Do not use vague labels like "conversational" or "professional" without concrete examples.

### 1. Voice and Tone
- Overall register (formal/informal spectrum — where exactly, with evidence)
- How they signal expertise (credentials, examples, authority, none?)
- How they handle opinions (direct assertion, hedged, evidence-first?)
- Humour (type, frequency, or absence)

### 2. Sentence Patterns
- Typical sentence length (short/mixed/long — estimate range)
- Opening patterns (how they start paragraphs and pieces)
- Use of fragments, questions, imperatives
- Rhythm (short-short-long? consistent? varied?)

### 3. Vocabulary
- Register level (plain language, domain jargon, academic, casual)
- Signature words or phrases they use repeatedly
- Contractions (always/sometimes/never)
- Words they notably avoid

### 4. Structure
- How they open pieces (hook style)
- How they close pieces (CTA, summary, open question)
- Section/paragraph length preferences
- Use of lists, headings, bold, code blocks

### 5. Anti-Patterns
- 3-5 things they consistently never do (with evidence of absence)
- Structures, tones, or approaches absent from all samples

## Output Format

Produce the profile in this exact structure:

```
## Voice Summary
[2-3 sentences capturing the most distinctive aspects of this writer's voice]

## Sentence Patterns
- Default length: [specific range]
- Variation: [pattern]
- Openers: [typical patterns with examples]
- Fragments: [frequency and purpose]

## Vocabulary
- Register: [specific description]
- Signature phrases: [list 3-5 with frequency]
- Contractions: [always/sometimes/never]
- Avoids: [words they never use]

## Structure
- Opens with: [pattern]
- Closes with: [pattern]
- Paragraphs: [length and rhythm]
- Visual elements: [lists, bold, code, etc.]

## Voice Markers
1. [Most distinctive feature — with evidence quote]
2. [Second most distinctive]
3. [Third most distinctive]

## Anti-Patterns
- Never: [pattern 1]
- Never: [pattern 2]
- Never: [pattern 3]

## Banned Words
[Words from the standard AI cliché list that this writer never uses. Only include words that are genuinely absent from all samples. Format as comma-separated list.]

## Audience
- Writes for: [inferred reader role/expertise]
- Assumes reader knows: [assumed knowledge]
- Tone calibration: [formality 1-10, directness 1-10, jargon tolerance 1-10]
```

Keep the analysis under 1,500 words. This is a quick profile, not the full Creator Profile Builder output — prioritise the most actionable patterns over exhaustive coverage.
