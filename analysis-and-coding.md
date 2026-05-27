# Analysis and Coding

Qualitative analysis is the work of turning a pile of transcripts, notes, photos, and video into a small number of clearly-stated findings supported by evidence. Done well, it produces insight that survives scrutiny. Done badly, it produces "what I heard most" reported as fact.

This file covers transcription, the basics of coding, thematic analysis, framework analysis, saturation, software, AI-assisted approaches, and the common mistakes beginners make.

---

## The Mindset

Quantitative analysis tries to estimate parameters. Qualitative analysis tries to surface patterns of meaning. The mental model is different:

- **You are not counting.** Even if you make a tally of how many participants said X, that tally is for your own use as an analyst, not for the report.
- **You are looking for patterns and contrasts.** What did multiple participants say? Where did they diverge? What did one person say that recasts how you should read what others said?
- **You are building a story, not a database.** The end product is an interpretive account that tells a reader something they did not know.

A useful tension to hold throughout: stay close to the data, and also be willing to abstract from it. Quotes alone are not findings. Findings alone, without quote evidence, are claims. Good analysis links the two.

---

## Step 1: Transcribe

Before analysis, you need a transcript. Three approaches:

1. **Verbatim transcription by a service.** Rev, GMR Transcription, TranscribeMe. Cost: $1 to $2 per minute. Quality: high. Turnaround: 12 to 48 hours.
2. **AI transcription with human review.** Otter, Descript, Sonix, MS Teams transcripts. Cost: low or free with a subscription. Quality: ~85 to 95 percent accurate; better with clear audio and one speaker at a time. Always review and clean.
3. **Self-transcription.** Slow but produces deep familiarity with the data. Useful for small studies (5 IDIs) or when the analyst is the moderator.

A verbatim transcript captures every word, every "um," every false start. A cleaned transcript edits out fillers. For coding, verbatim is more useful (fillers and hesitations carry meaning). For quoting in a report, clean and light-edit for clarity.

If working with AI transcription, listen back to key passages while reading the transcript. AI mishears domain-specific words, brand names, and emotion-laden phrases in ways that distort meaning. The bigger the stake on a passage, the more carefully review it.

For non-English sessions, transcribe in the original language. Translate selectively (the quotes that will appear in the report) rather than translating the whole transcript.

---

## Step 2: Read Before You Code

The single most underappreciated step. Before opening a coding tool, read each transcript once, top to bottom, with no agenda except to understand what happened in that session.

While reading, jot brief notes:

- What were the most striking moments?
- What is this participant's broad story (their stance, their experience, their language)?
- What surprised you?
- What did you expect to hear that you did not?
- What words and phrases are showing up that you would not have predicted?

These notes become the spine of your interpretation. They prevent the most common analysis failure, which is coding so closely to the data that you lose sight of the big picture.

For multi-session studies, read 3 to 5 transcripts before coding begins. You will notice patterns informally that will save coding work.

---

## Step 3: Build a Starter Codebook (Framework First)

Coding is the act of attaching short labels to chunks of meaning in the data. A code is a tag. A chunk can be a sentence, a paragraph, or a longer passage. The job of coding is to make the data searchable, sortable, and comparable across participants.

For commercial qual, the dominant working approach is **framework-first**: build a small starter codebook (around 10 codes plus an "other" bucket) before you do systematic coding, then refine as you go. This is different from the academic orthodoxy of pure open coding, where codes emerge from the data and you end up with 80 to 150 codes that have to be consolidated later. Pure open coding is methodologically sound, but for a beginner with a real deadline it is overwhelming, slow, and produces a coding system that no one can apply reliably.

### Why a small codebook matters

Three reasons.

1. **You can hold around 10 codes in your head.** You cannot hold 30 or 50. When you cannot, you lose consistency: two passages that should get the same code get different ones, and the analysis stops being reliable.

2. **Inter-coder reliability is achievable with a small codebook.** With 10 codes, two analysts coding the same transcript can reasonably agree on around 80 percent of passages, which is the working standard. With 50 codes, agreement drops well below that, and the coding stops being defensible.

3. **The report is built from codes.** Every code is a potential row in the synthesis matrix or a potential finding. 10 codes produce a focused report. 50 produce noise.

### Practical method

1. **Re-read the research objectives.** Each objective points to a small number of expected codes. A study about onboarding will have codes for the moments of the onboarding journey (signup, first transaction, first day, first week). A product evaluation study will have codes for the criteria (efficacy, ease, cost, support).

2. **Skim two or three transcripts.** Not deep coding, just read. Notice the topics that come up that you did not predict from the objectives. Add those as candidate codes.

3. **Draft a starter codebook of about 10 codes.** Each code gets a short label, a one-sentence definition, and one or two example passages. Include the expected codes from the objectives and the surprising-but-recurring topics from your read. Twelve codes is the practical ceiling for most commercial projects. If you are pushing toward 15, you are probably not consolidating enough.

4. **Add an "other" bucket.** Every codebook needs a catch-all for material that does not fit the existing codes. The "other" bucket is part of the discipline, not a failure of it.

### Example starter codebook (SaaS onboarding study)

| Code | Definition | Example trigger |
|---|---|---|
| Signup decision | Why and how the participant chose this product | "I'd been looking at three options and..." |
| First-session experience | What happened in the first 30 minutes after signup | "I just clicked around for a while before..." |
| Help-seeking | When and how the participant looked for help | "I searched the help docs but..." |
| Human moment | Any moment of human contact (chat, peer, friend) | "Then I texted my friend who uses it..." |
| Friction point | A specific moment of getting stuck | "It wouldn't let me add my second account..." |
| Almost-quit | The participant came close to giving up | "I almost just deleted it that night..." |
| Comparison to alternative | Reference to a competing product | "It's different from how [other product] does it..." |
| Recommendation behaviour | Whether/how they would recommend | "I wouldn't tell my friends to use it..." |
| Emotional language: positive | Explicit positive emotional language | "I was thrilled when..." |
| Emotional language: negative | Explicit negative emotional language | "I was so frustrated I..." |
| Other | Anything worth marking that doesn't fit | (catch-all) |

That is 10 codes plus "other". A first-time analyst can hold this in mind. A reviewer can verify the coding. The report has clear scaffolding.

### The 5 percent rule for "other"

When you finish coding (or pause partway), count the passages tagged "other". If they exceed 5 percent of all coded passages, something is missing from the codebook. Read the "other" passages and look for the pattern that connects them. Add one new code for the dominant pattern, recode the relevant passages from "other" into the new code, and continue.

Repeat until "other" sits at 5 percent or below. Most projects do this once or twice. If you find yourself needing to add a fourth or fifth new code, your starter codebook was too narrow and you may want to revisit the objectives.

### Types of codes you may include

Different code types serve different jobs. A good starter codebook usually mixes a few of these:

- **Descriptive codes.** What is happening, who is doing what. "Logs in for the third time," "calls customer service."
- **Process codes.** Action-oriented. "Working around the bug," "ignoring the prompts."
- **Emotion codes.** "Frustrated," "delighted," "anxious." Mark when emotion is explicit or strongly implied.
- **In vivo codes.** The participant's own words. "Beating my head against a wall." Worth tagging when the phrase is distinctive and recurring.
- **Categorical codes for expected vs. surprising.** Some analysts add a flag to each passage marking whether the content was expected from the brief or surprising. The surprising material is often where the strongest findings live.

### When to use pure open coding instead

Framework-first works for most commercial qual. Pure inductive open coding (letting codes emerge with no starter framework, starting with 30 to 50 codes and consolidating down) is the right call when:

- The study is purely exploratory and you genuinely do not know what to expect.
- The phenomenon is unfamiliar to the team and you cannot predict the categories.
- You are doing academic-leaning work (grounded theory, phenomenology) where the methodology requires it.

Even in these cases, the goal is a final codebook of around 10 to 15 codes plus "other" by the time you are coding systematically. The path is different (more codes initially, then consolidate), but the destination is the same.

---

## Step 4: Code the Transcripts

With the starter codebook in hand, code the transcripts systematically.

1. Open a transcript. Read a passage. If it matches a code in the codebook, tag it with that code.
2. If it does not match any existing code, tag it "other" and move on. Do not stop to invent a new code mid-pass; that breaks consistency.
3. Memo as you go. When a passage triggers a thought that goes beyond a tag, write it in a separate memo file. The memos become the early findings.
4. Stay disciplined about consistency. If you tagged a similar passage with "friction point" in interview 1, tag the analogous passage in interview 6 the same way.
5. After every 2 to 3 transcripts, pause. Re-read your "other" passages. If a pattern is clear, add it as a new code (and recode the relevant "other" passages into it). Apply the 5 percent rule.
6. By the time you finish coding, your codebook should be stable: around 10 to 13 codes plus "other" sitting at or below 5 percent.

If you are using AI-assisted coding, the same discipline applies. See the AI-Assisted Coding section below.

---

## Step 5: Check Coding Consistency (Inter-coder Reliability)

Before you treat your coded data as the basis for findings, check whether the coding is consistent. If you applied the same code inconsistently across transcripts, your findings rest on noise.

The formal version of this check is **inter-coder reliability** (ICR). Two analysts code the same transcript independently, then compare. The agreement rate tells you whether the codebook is being applied consistently. In academic work, the standard measure is Cohen's kappa or percent agreement, with 80 percent agreement (or kappa above 0.7) treated as the threshold for defensible coding.

### Why this matters more with bigger codebooks

The math is the discipline. With 10 codes plus "other," two analysts can plausibly agree on 80 percent of passages because each passage has a small, distinct set of plausible labels. With 30 or 50 codes, the same passage might reasonably get any of several labels, and agreement falls below the defensible threshold. This is one of the strongest reasons to keep the codebook small.

### The simple commercial version

Most commercial qual does not run formal kappa calculations. The working norm is lighter but still real:

1. **Pick one or two transcripts you have already coded.** Pick ones near the middle of the study, after you have stabilized on the codebook.

2. **Have a second person code them independently.** A colleague, a peer reviewer, or a junior team member. Give them the codebook (with definitions and example passages) and nothing else. Do not show them your coding.

3. **Compare.** Go passage by passage. Where do you agree? Where do you disagree? For disagreements, talk through them. Is the codebook ambiguous? Is one of you reading the passage wrong? Do you need to refine a code definition?

4. **Refine the codebook based on the disagreements.** Most disagreements come from ambiguous code definitions. Tighten the language.

5. **Re-code the transcripts you already finished with the refined codebook.** Quick pass; the second coder's work usually surfaces only a handful of changes.

If the two coders agree on roughly 80 percent of passages, the codebook is working. If agreement is below that, the codebook is too fuzzy and needs tightening.

### When ICR is non-negotiable

- Studies where the findings will be challenged (regulatory, legal, M&A-related, or any context where a stakeholder will push back).
- Studies where the analysis is being done by someone other than the moderator and the moderator is reviewing.
- Studies that will be published or shared widely.
- Studies with high enough sample size that codebook drift is a real risk (more than 15 transcripts).

### When informal consistency checks are enough

- Small studies (6 to 8 IDIs) coded by a single analyst over a short window. The risk of drift is low; the cost of a formal check is disproportionate. Self-discipline (re-reading your own coding decisions) is usually sufficient.
- Exploratory studies where the codebook is still evolving and the findings are explicitly directional.

Even in these cases, doing a 30-minute self-audit (re-read your codebook, re-read a coded transcript, ask "am I applying this consistently?") catches the most common drift problems.

### What it looks like in practice (a working example)

A 12-IDI study on B2B onboarding. After coding 6 transcripts, the analyst pauses for a consistency check. A colleague codes the most recently completed transcript independently. They compare.

> "Of 78 coded passages in the transcript, we agreed on 64 (82 percent). Of the 14 disagreements:
> - 6 were ambiguous between 'friction point' and 'help-seeking'. We agreed to tighten the definition: 'friction point' is when the participant got stuck and stopped; 'help-seeking' is when the participant took action to get unstuck. The definitions now make the call clearer.
> - 4 were ambiguous between 'comparison to alternative' and 'recommendation behaviour' when participants said things like 'I'd recommend it over [other product]'. We agreed to tag these with both codes.
> - 3 were passages one of us coded and the other did not. We agreed they were borderline and either treatment was defensible.
> - 1 was a clear coding error on my part."

The analyst updates the codebook, re-codes the 6 already-completed transcripts (light pass), and continues to interview 7. The ICR check took about 90 minutes total and significantly tightened the defensibility of the final analysis.

---

## Step 6: From Codes to Themes (and Finding Statements)

In framework-first coding, your codes are often already at or near the theme level. The job at this stage is less about clustering codes into themes (since the structure is already there) and more about **refining each code into a finding statement** the report can use.

A code says "people mentioned X." A finding says "across the study, people experience X in this way, for these reasons, with these consequences."

Practical method:

1. Take each code in your codebook. Pull together every passage tagged with that code.
2. Read across the passages. What is the pattern? Where do participants agree? Where do they diverge?
3. Write a one- to two-sentence finding statement for each code that holds enough material to be a finding.
4. Some codes will not become findings. They were useful for organizing the data but the pattern across passages is too thin to warrant reporting. That is fine. A starter codebook of 10 codes typically produces 5 to 7 findings.
5. Some findings may pull from multiple codes. (Example: a finding about the "human moment" might draw from the human-moment code and the help-seeking code together.) That is also fine.

Finding statements should be:

- **Stated as findings, not as topics.** "Onboarding" is a topic. "First-time users feel overwhelmed in the first 48 hours and look for a familiar face inside the platform to anchor them" is a finding.
- **Supported by evidence from multiple participants.** A single-participant pattern is a case story, not a finding. Note it separately, do not generalize.
- **Specific enough to be useful.** "Customers want better experiences" is too vague. "Customers expect onboarding to be done by end of session one, and are willing to forgive small issues if they can get a transaction done that day" is specific.

### When to consolidate further

If, after refining each code into a finding, you have more than 7 findings, look for opportunities to consolidate. Two findings may be variants of the same underlying pattern. The report is easier to land with 5 to 7 strong findings than with 10 thinner ones.

If you have fewer than 4 findings, look back at your codebook. You may have collapsed too early.

---

## Step 7: Look for Contrasts, Negative Cases, and Surprises

A common beginner failure is to find the theme that fits the most data and stop. The strongest analyses also surface:

- **Contrasts.** Where does the theme not hold? Which participants are the exceptions? Why?
- **Negative cases.** Participants whose data cuts against the dominant theme. Do not hide them. Often they are where the most interesting refinement lives.
- **Surprises.** Things you did not expect to hear. These are often the most decision-relevant findings because they reset the team's mental model.

In the report, name the contrasts and the negative cases. A finding stated alongside its exceptions reads as more credible, not less.

---

## Step 8: Memoing

Memos are notes you write to yourself throughout coding. They capture in-progress thinking that will not fit in code labels.

A useful memo might be:

> "Across the four onboarding interviews so far, the people who succeed all mention a specific moment when they connected with a real human: chat support, a peer in a forum, a Slack DM with a salesperson. The people who fail describe a sense of being on their own. Worth checking: is the differentiator the human moment, or is it that the people who succeed are more proactive in seeking help? The current data leans toward the former but I should probe this in interview 7."

Memos are not findings yet. They are working hypotheses. By the end of coding, your memos will largely become the bullet points of the report.

A good rhythm: open a memo file at the start of each coding session, append to it as you go, save it with the project files.

---

## Step 9: Saturation

Saturation is the moment when fresh transcripts stop producing fresh codes. It is the practical answer to "how many is enough."

In commercial work, saturation is usually reached at:

- 6 to 8 IDIs within a homogeneous segment
- 2 to 3 focus groups within a segment
- 12 to 16 IDIs across mixed segments

If you have run the planned number of sessions and still keep hearing new things, you have not saturated. Run more if budget allows or be honest in the report that the work scoped the territory but did not exhaust it.

If you have run the planned number and the last 3 sessions produced no new codes, you have saturated. The remaining work is to integrate, not to collect.

Saturation is not the same as "I have heard the same thing several times." It is "fresh material stops producing fresh insights."

---

## Approach: Thematic Analysis (Framework-First Variant)

Thematic analysis (Braun and Clarke is the most-cited reference) is the workhorse of commercial qual. Their six-phase method assumes a more inductive approach (codes emerge from the data before themes). The commercial variant most beginners should use is a deductive-inductive hybrid: start with a framework drawn from the research objectives, refine inductively as you go.

The phases adapted for commercial work:

1. **Familiarize.** Read everything once with no coding.
2. **Build a starter codebook.** Around 10 codes plus "other", grounded in research objectives.
3. **Code systematically.** Apply the codebook. Use the 5 percent rule for "other".
4. **Check consistency.** Either a self-audit or a second-coder check on at least one transcript.
5. **Refine codes into findings.** Each code becomes a finding statement (or is merged with another code into one).
6. **Produce the report.** Write up.

Thematic analysis is method-agnostic about epistemology, which is part of why it travels so well into commercial work. Use it when you do not need a specific theoretical commitment.

---

## Approach: Framework Analysis

Framework analysis (Ritchie and Spencer) is a more structured approach often used in applied research where you have specific research questions you need to answer.

The method:

1. Familiarize.
2. Identify a thematic framework (often derived from the research questions plus emerging themes).
3. Build a matrix: rows are participants, columns are themes.
4. Fill the matrix by extracting and summarizing what each participant said on each theme.
5. Interpret across the matrix: patterns across participants within a theme, patterns across themes within a participant.

The matrix approach makes contrasts visible. It also produces a concrete artifact (the filled matrix) that supports the report.

Use framework analysis when you have predefined research questions you need to answer systematically. Use thematic analysis when you are more open-ended.

---

## Approach: Grounded Theory (Lite)

Pure grounded theory is for academic theory-building and rarely fits commercial timelines. But the disciplines of grounded theory (constant comparison, theoretical sensitivity, axial coding) are useful even in shorter projects:

- **Constant comparison.** Compare each new piece of data to what you have coded so far. Does it fit existing codes, refine a code, contradict, or open a new dimension?
- **Axial coding.** After open coding, group codes by their relationships: conditions, actions, consequences. This produces richer themes than flat clustering.
- **Selective coding.** Pick the core category that organizes the others. The "story" of the analysis runs through this core.

Use grounded theory moves when you are exploring a poorly understood phenomenon and need a coherent model out the other side.

---

## Software

A coding software (CAQDAS, computer-assisted qualitative data analysis software) supports the work but does not do it for you. The software helps you tag, retrieve, and visualize codes. The interpretation is yours.

Common tools:

- **NVivo.** Industry standard. Powerful, full-featured, has a steep learning curve. Best for larger projects (20+ transcripts) with a team. Annual subscription.
- **Atlas.ti.** Similar in scope to NVivo. Some prefer its interface.
- **Dedoose.** Web-based, lighter weight, easier to learn. Subscription per month.
- **MaxQDA.** Strong on mixed-methods (qual plus quant).
- **Quirkos.** Designed to be beginner-friendly, visual.
- **Delve.** Web-based, simple, designed for thematic analysis with teaching materials.
- **Microsoft Word with comments and color-coding.** For studies of 5 to 8 IDIs, this is honestly fine. Highlight passages, comment with codes, use the document for navigation.
- **A spreadsheet.** A two-column "quote / code" sheet works for small projects.

Do not buy software you do not need. For studies of 12 or fewer transcripts, Word or a spreadsheet is sufficient. For larger studies and team projects, the investment in NVivo or Dedoose pays back.

---

## AI-Assisted Coding and Synthesis

AI tools change how qual analysis is done in 2025 and beyond. Used well, they accelerate the early and mechanical phases of analysis. Used badly, they produce plausible-sounding but shallow findings that miss what matters. The discipline is to use AI as a **first pass and as a coding-guide builder**, not as a replacement for manual coding.

### The Two High-Value Uses

**Use 1: First-pass scan to find candidate themes and surprises.**

Before you start manual coding, feed the transcripts to an AI (Claude, ChatGPT, Gemini) and ask:

- "Read these 10 interview transcripts. What recurring topics do you notice? What do participants say about [topic of interest]? What surprises you about the language they use?"
- "Pull every passage where a participant talks about [specific topic] and group them by sentiment."
- "Across these transcripts, what are 5 to 8 candidate themes that could organize a report? Give me a short description and one example quote for each."

The AI's answer is a starting point, not a finding. It accelerates familiarization. It surfaces patterns you may otherwise miss. It does not produce final analysis, because it has no domain context and no interpretive judgment.

**Use 2: Build the starter codebook, then manually code.**

This is the most powerful AI workflow in commercial qual. The pattern:

1. Give AI the research objectives and 2 to 3 transcripts. Ask it to propose a starter codebook of around 10 codes, plus an "other" bucket, with a short definition and one or two example passages for each. (You can give it the example codebook from Step 3 as a template if helpful.)
2. Review the AI-proposed codes. Discard the ones that do not feel useful. Consolidate the ones that overlap. Rename the ones in generic language ("frustration") to use the participants' actual vocabulary ("beating my head against a wall"). Aim to land at around 10 codes plus "other".
3. You now have a starter codebook drafted in a fraction of the time it would have taken to build from scratch.
4. Manually code the transcripts using this codebook. The manual coding is where the interpretation happens, and is non-negotiable. AI can propose; only the analyst can decide.
5. Apply the 5 percent rule for "other" as you go. If the "other" bucket grows, ask AI to look at the "other" passages and propose what they have in common. Use that as a starting point for whether to add a new code.
6. Update the codebook as you go.

This workflow gets the speed benefit of AI without sacrificing the interpretive depth that makes qual valuable. The AI does the mechanical work (drafting, sorting, retrieving); the human does the judgment work (deciding what matters, deciding what it means).

A warning specific to AI-proposed codebooks: AI tends to propose more codes than you need, and to propose codes in generic categorical language ("Customer satisfaction," "Product feedback"). Be ruthless about consolidating and renaming. The codebook you actually use should sound like your study, not like a generic market research template.

### Other Useful AI Uses

- **Transcript cleaning and summarization.** Reliable. AI can produce a 1-page summary of an interview, identify key moments, pull quotes.
- **Quote retrieval.** Strong. "Find me three quotes about confusion with the dashboard from the second-round interviews." AI is good at search.
- **Pattern recognition across transcripts.** Useful. "Across these 10 transcripts, what do participants 1, 4, 7, and 9 share that the others do not?" Verify before relying.

### What AI Cannot Do Well

- Interpret emotion, hesitation, contradiction, irony. AI takes words at face value.
- Distinguish what was said from what was meant. Sarcasm, deflection, social desirability are invisible to it.
- Bring outside context (knowledge of the client's strategy, the competitive landscape, the human stakes).
- Refuse a request that does not fit the data. AI will manufacture a plausible answer when the data does not support one. This is the single most dangerous AI failure mode in qual: confident hallucination.
- Replace the moderator's reading of the room. AI cannot tell you which moments mattered in the session.

### The Non-Negotiable: Manual Coding Stays in the Workflow

Do not use AI to produce final coding without manual review. The temptation to skip manual coding when AI seems to be doing fine is strong; resist it. Here is why:

- AI coding tends toward generic language ("frustration," "satisfaction") that washes out the specificity that makes qual useful.
- AI misses the unexpected. Its training pulls it toward the average; the average is rarely the most insightful pattern.
- A claim in your report that traces back only to AI-proposed coding is hard to defend under scrutiny. A claim that traces back to your manual coding of specific passages is defensible.

### Recommended Workflow

1. **Read** all transcripts manually. AI does not substitute for this. Familiarization is where you build the mental model that all later steps depend on.
2. **First-pass AI scan.** Ask AI for candidate themes and surprises. Note what it finds; do not yet treat these as findings.
3. **AI-assisted starter codebook.** Ask AI to propose around 10 codes (plus "other") from the research objectives and 2 to 3 transcripts. Curate ruthlessly: discard, consolidate, rename. Land at around 10 codes that match your study, not a generic template.
4. **Manual coding.** Code the full set of transcripts yourself, applying the codebook. Apply the 5 percent rule for "other" as you go. Update the codebook only when the data clearly demands a new code.
5. **Consistency check.** Have a second person code one transcript independently. Compare. Refine the codebook based on disagreements. Re-code if needed.
6. **AI-assisted finding-statement drafts.** For each code, pull the tagged passages and ask AI to draft a one- to two-sentence pattern statement. This is a starting point; you write the actual finding.
7. **Manual interpretation and finding refinement.** You do the work of saying what the data means, what is robust, and what the implications are.
8. **AI-assisted quote retrieval.** Ask AI to find supporting and disconfirming quotes for each finding. Verify each one against the transcript.
9. **Manual final review.** Read everything end to end. Verify every claim traces to data you can show.

### Specific AI Tools

- **General LLMs (Claude, ChatGPT, Gemini).** Fine for first-pass scans, coding guide proposals, quote retrieval, draft writing. Use long-context modes for full-transcript work.
- **Marvin, Notably, Looppanel, Insight7.** Specialized AI qual tools with built-in coding interfaces, theme suggestions, transcript management. Useful at modest scale.
- **NVivo and Atlas.ti AI features.** Increasingly built into the established CAQDAS tools. Works well if you already use these platforms.

### A Working Principle

Treat AI as a fast, eager, slightly-confused junior analyst. It can do a lot of work in a fraction of the time. It will also confidently produce work that is shallow, generic, or wrong. Your job is to direct it, review it, and use it for the parts of the work where its speed is an unambiguous gain. Do not give it the parts of the work where interpretive judgment matters most: theme definition, what the findings mean for the client, what to say in the executive summary.

---

## Common Analysis Mistakes Beginners Make

1. **Coding before reading.** Skips familiarization, locks the analyst into early impressions.

2. **Code count as evidence.** "12 participants mentioned X." A count is not an analysis. Look at what they said, not just that they said it.

3. **Counting in the report.** "75 percent of participants felt overwhelmed" misrepresents qual data as if it were a survey. Use "many," "some," "a few," "one."

4. **Confirming the brief.** The client's hypothesis was X. The analyst codes the data through the lens of X. Disconfirming evidence is dismissed as "noise." Counter this by deliberately coding for the opposite of each expected finding.

5. **Ignoring negative cases.** Findings stated without their exceptions read as overclaim. Surface exceptions.

6. **Themes that are topics.** "Pricing" is a topic. "Pricing is the moment participants pause to weigh their options" is a theme.

7. **One participant becomes the finding.** A vivid quote from one participant turns into a generalized claim. Distinguish the case from the pattern.

8. **No memoing.** Without memos, the analyst loses the in-progress thinking that becomes the report.

9. **Coding everything.** Some passages do not carry meaning. Not every line needs a code.

10. **Too many codes.** A codebook of 30 or 50 codes is unmanageable for a single analyst, impossible to apply reliably across coders, and produces noise rather than signal. Aim for around 10 codes plus "other".

11. **No "other" bucket.** Without "other", you either force-fit passages that do not belong (distorting the analysis) or skip them (losing data). The bucket is the discipline.

12. **No consistency check.** Coding feels arbitrary after a few transcripts. A simple second-coder check (or a self-audit) catches drift.

13. **Treating AI outputs as final.** Plausible language is not validated insight.

14. **Stopping at codes.** Codes are not findings. Findings are statements about patterns of meaning, supported by evidence, that inform a decision. The work is not done when coding is done.

---

## What the Output Looks Like

By the end of analysis, you should have:

- A working codebook (around 10 codes plus "other" sitting at or below 5 percent of passages, with definitions and example quotes).
- 5 to 7 findings, each with a one- to two-sentence statement and the codes that support it.
- A memo file with in-progress thoughts, hypotheses, and surprises.
- A quote bank: 3 to 8 strong verbatim quotes per finding, lightly cleaned for readability with edits marked.
- A list of negative cases and contrasts.
- A note on saturation: where you got to and what remained open.
- A consistency check (formal or informal): a record that the coding was applied reliably.

These artifacts feed directly into the report.

---

## Routing Forward

Once analysis is complete:

- Move to: `reporting-and-insights.md`
- Also revisit: `ethics-and-validity.md` for what to include about trustworthiness in the report
