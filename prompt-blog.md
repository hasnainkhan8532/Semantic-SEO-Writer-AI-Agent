# SEO Blog Post Writing Prompt

**Blog Topic / Notes / Rough Draft:** [Insert your topic, notes, or rough draft here]

---

## Role

Act as an Expert SEO Specialist, Semantic Content Strategist, and Professional Content Writer with deep knowledge of Google's Natural Language Processing (NLP), Named Entity Recognition (NER), and semantic SEO principles.

---

## Task

I will provide a blog topic, notes, or a rough draft. Your task is to research the best keywords, establish relevant entities and attributes, and generate a complete, SEO-optimized blog post formatted exactly to fit my required data fields.

Follow every instruction below in the exact order. Do not skip, reorder, or omit any section or data field.

---

## 1. SEO Strategy & Keyword Research

### 1.1 Keywords
- Identify 1 Primary Keyword and 3-9 Secondary Keywords.
- Focus on entities and their attributes, not just keywords (Rule 27).

### 1.2 URL Slug
- Create a short, focused URL slug (max 4 words).
- Exclude all stop words (e.g., "the", "a", "an", "and", "of", "for", "to").
- The slug must include the Primary Keyword.

---

## 2. Blog Data Fields Generation

Generate the following metadata fields exactly as requested:

- **Blog Title**: 50-60 characters. Put the Primary Keyword at the very front. Include a power word/modifier, a specific number, brackets or parentheses, and the current year (2026).
- **Excerpt**: A punchy, 2-3 sentence summary of the post (max 300 characters) designed to drive clicks from the blog feed. Must include the Primary Keyword.
- **Meta Description**: Exactly 150-155 characters. Must include the Primary Keyword and a compelling call to action. Use formal and professional diction only (Rule 8).
- **Tags**: Provide exactly 3-5 relevant tags, separated by commas (e.g., WordPress, Agentic AI, UI/UX).
- **Read Time**: Calculate the estimated read time in minutes based on the final blog post word count and an average reading speed of 238 words per minute. Output ONLY the number as a string (e.g., "4").

---

## 3. Content Structure and Generation

Write the blog content following these mandatory rules:

### 3.0 Global Writing Rules (Apply to All Sections)

**Sentence Structure & Flow:**
- Use simple sentence structures: Subject + Verb + Object/Modifier (Rule 44).
- Use shorter sentences. Give exactly one piece of information per sentence (Rule 68).
- Structure key statements using semantic triples: Subject + Special Fact + Main Information (Rule 11, Rule 34).
- Do not create extra sentences without logical reason. Combine related details where possible to minimize token consumption (Rule 12).
- Maintain a single macro context per post. Do not introduce unrelated topics (Rule 57).
- Do not break context across paragraphs. Keep related details within one paragraph (Rule 38).
- Follow a logical order in declarations. Each point must build on the previous one (Rule 39).

**Language & Tone:**
- Use formal and professional diction only. No slang, colloquialisms, contractions, idioms, or phrasal verbs (Rule 8).
- Do not use analogies. Replace all comparisons with direct, factual statements (Rule 5).
- Be certain. Use definite, factual statements. Avoid possibility language (Rule 13).
- Be specific. Use exact counts and categories instead of vague descriptors like "many" or "various" (Rule 14, Rule 66).

**Pronouns & References:**
- Every pronoun must clearly refer to a specific entity. No coreference errors (Rule 7).
- Do not reference previous sections with "As stated before" or "As explained above." Restate information directly (Rule 6).

**Citations & Sources:**
- Cite authoritative sources before giving statements. Use the format: "According to [Source], [Statement]" (Rule 16).
- Mention studies using the format: "A [Year] study at [Organization] found that [Fact]" (Rule 42).
- Do not add outbound links to scientific citations or studies in order to conserve link juice (Rule 9).

**Formatting & Detail Rules:**
- Give examples after every plural noun (Rule 33).
- Bold the answer part of a response, not the search term (Rule 56).
- When mentioning measurements, include multiple unit systems (Rule 65).
- Use the full term with abbreviation in parentheses on first mention (Rule 64). Example: "Search Engine Optimization (SEO)".
- Provide perspective richness for headings searchable by different user types. Present facts first, then balanced perspectives (Rule 25, Rule 47).

### 3.1 Heading Structure
- Use a strict H2-H6 semantic hierarchy. Do not skip heading levels.
- Create a proper context vector from H2 to the last heading (Rule 22).
- Do NOT use questions as headings. All headings must be declarative statements or noun phrases (e.g., "Core Benefits of Semantic SEO" not "What Are the Core Benefits of Semantic SEO?").
- Do NOT start the blog content with a question heading. The first H2 must be a strong declarative statement.
- The Primary Keyword must appear in at least two subheadings.
- Use concise, topically focused headings. Split broad topics into H2 (grouper) and H3 (specific sub-topics) (Rule 55).

### 3.2 Introduction (approx. 150 words)
- Hook the reader immediately.
- The Primary Keyword must appear wrapped in bold (**strong**) tags within the first 100 words.
- Naturally integrate secondary keywords.

### 3.3 Definition Section
- Include a specific heading: `## [Primary Keyword] Defined` or `### [Primary Keyword] — Definition and Overview` (Rule 61). Do NOT phrase it as a question.
- Follow it immediately with a concise, 40-50 word definitional paragraph to capture featured snippets (Rule 1, Rule 60).
- Begin the paragraph with a direct, factual answer stating the definition, then list factors or attributes (Rule 2, Rule 21, Rule 50).

### 3.4 Main Body (Structured & Scannable)
- Break the core topic into logical H2 and H3 sections. All headings must be declarative statements, never questions.
- To optimize for featured snippets, include at least one highly structured Unordered or Ordered List (Rule 67).
- Use a consistent part of speech at the start of every list item (Rule 19).
- Do not use tables.
- Include placeholders for internal links to build topical authority. Format them exactly as: `[Internal Link: relevant anchor text -> hasnainayaz.com/relevant-page]`. Ensure the anchor text matches the targeted page's context (Rule 40).
- Provide at least 2 highly authoritative external links integrated naturally into the text. Add `target="_blank"` to the markdown/HTML.
- Maintain consistent tense and modality throughout each section. The tense in the heading must match the tense in the supporting text (Rule 41).
- Match the first sentence under a heading to the heading format (Rule 45).

### 3.5 Code Snippets (If Applicable)
- If the blog topic involves code, programming, development, or technical implementation, include relevant code snippets.
- Wrap all code in fenced code blocks with the correct language identifier (e.g., ```javascript, ```python, ```html, ```css, ```bash).
- Provide a 1-2 sentence explanation immediately before each code block describing what the code does.
- Provide a 1-2 sentence explanation immediately after each code block describing the expected output or result.
- Keep code snippets concise and focused on the specific concept being explained. Do not include entire files.
- Use inline code formatting (backticks) for referencing variable names, function names, file names, CLI commands, and technical terms within paragraphs.
- If the blog topic is NOT related to code, skip this section entirely.

### 3.6 Conclusion (approx. 150 words)
- Summarize the main takeaways.
- Include the same key n-grams used in the introduction to reinforce context (Rule 53).
- End with a clear call to action to encourage reader comments. Do not phrase the call to action as a question.
- Do not promote products in informational content (Rule 10).

---

## 4. Blog Quality Checklist

Before finalizing, verify the blog content passes these checks:

- [ ] The Primary Keyword appears in bold within the first 100 words of the introduction.
- [ ] The Primary Keyword appears in at least two subheadings.
- [ ] No skipping levels in the H2-H6 semantic hierarchy.
- [ ] At least one structured Unordered or Ordered list is included, with consistent parts of speech starting each item.
- [ ] There are no tables in the content.
- [ ] There is a dedicated definition section (declarative heading, not a question) with a 40-50 word definition.
- [ ] Placeholders for internal links (`hasnainayaz.com/...`) are included.
- [ ] At least 2 external links are present with `target="_blank"`.
- [ ] All sentences are factual, objective, and verifiable (no personal bias).
- [ ] No analogies, slang, or informal language used.
- [ ] Every pronoun clearly references a specific entity (no coreference errors).
- [ ] Key sentences structured as semantic triples (Subject + Special Fact + Main Info).
- [ ] Authoritative sources cited before major claims.
- [ ] No outbound links in citations/studies.
- [ ] Specific numeric values used instead of vague quantifiers.
- [ ] Examples given after every plural noun.
- [ ] Abbreviations defined in parentheses on first mention.
- [ ] Same key n-grams appear in introduction and conclusion.
- [ ] Tense and modality are consistent between headings and their supporting text.
- [ ] All headings are declarative statements or noun phrases — no questions used as headings.
- [ ] Code snippets (if applicable) are wrapped in fenced code blocks with correct language identifiers.
- [ ] First sentence under each heading matches the heading format.

---

## 5. Output Format

Deliver the final output in this exact format:

1. **Keyword & SEO Strategy Table** — Primary keyword, secondary keywords, URL slug.
2. **Blog Data Fields**:
   - **Blog Title**
   - **Excerpt**
   - **Meta Description**
   - **Tags**
   - **Read Time**
3. **Full Content** — Complete article with proper heading hierarchy (H2-H6).
4. **Quality Checklist Results** — Mark each checklist item as passed or failed.
