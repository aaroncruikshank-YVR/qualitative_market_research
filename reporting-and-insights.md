# Reporting and Insights

The report is the work the project is ultimately judged on. A skilled study with a weak report fails. A modest study with a sharp report can inform a real decision.

This file covers report structure, finding-evidence-implication writing, quote selection and editing, common deliverable formats, the difference between a topline and a full report, and the common mistakes beginners make.

---

## What a Qual Report Has to Do

A qual report serves three jobs at once:

1. **Inform a decision.** The buyer commissioned the research to make a decision. The report exists to give them what they need to decide. Anything that does not serve a decision is decoration.

2. **Educate the reader.** Most readers of a qual report did not sit in the sessions. The report has to give them enough context, enough voice, and enough specifics that they walk away with a working mental model of the population.

3. **Be defensible under scrutiny.** Six months later, a stakeholder who disagrees with a finding will push back. The report has to support its claims with evidence the reader can verify.

A common beginner mistake is to write the report as a record of what happened ("we ran 12 interviews, here is what each said"). That structure satisfies none of the three jobs. The right structure is: here is what we found, here is the evidence, here is what it means for the decision.

---

## The Finding-Evidence-Implication Structure

Each section of a qual report should follow a consistent pattern:

1. **Finding.** A clear, plain-language statement of what the research surfaced. One or two sentences.
2. **Evidence.** Quotes, examples, and observations that demonstrate the finding. Multiple participants where possible.
3. **Implication.** What this means for the decision the report is serving.

Worked example:

**Finding.** First-time users describe the first 48 hours after signup as an "alone in the dark" experience. The product feels capable; what they cannot tell is whether they are using it correctly. Most do not reach out to support until they have spent significant effort trying to figure it out themselves, and by then, several have already half-decided to give up.

**Evidence.**
- "I felt like I was clicking around hoping the thing I needed would just appear. There was no one to ask. I figured if I couldn't make it work, it was on me." (Bilal, retail business, signed up 14 days ago)
- "I almost gave up around day three. I had a problem with the tax setup and I just... I didn't know who to ask. I tried the help articles and they were too generic." (Lakshmi, professional services, signed up 8 days ago)
- "Eventually I gave up trying to figure it out and asked my brother-in-law. He uses [Platform X] for his business. He helped me on a video call that night." (Carlos, food service, signed up 22 days ago)

**Implication.** The product onboards adequately as a piece of software, but inadequately as a relationship. A user-side prompt to connect with a real human (in-app chat, scheduled onboarding call, peer community) during the first 24 to 72 hours may meaningfully change the early-cancellation curve. Worth testing.

This pattern repeats throughout the report. The reader can verify the finding by reading the quotes. The implication makes the so-what explicit.

---

## Report Structure

A typical qual report has these sections, in this order:

1. **Cover and project summary.** Title, dates, methodology in one line, scope in one line.
2. **Executive summary.** The 2 or 3 most important findings, each in one paragraph, with implications. One to two pages.
3. **Method and sample.** Who you talked to, how many, how recruited, what mode. One page. Include the screener criteria. This is the section that lets a reader assess transferability.
4. **Findings.** The body. 5 to 7 themes, each written in finding-evidence-implication format. Six to fifteen pages depending on study size.
5. **Negative cases and contrasts.** Where the patterns do not hold. One to two pages.
6. **Recommendations.** What to do with the findings. One to three pages. Frame as options or as testable hypotheses, not as definitive directives.
7. **What we did not learn.** Honest scope: what the study did not address, what would need follow-up. Half a page.
8. **Appendix.** Discussion guide, screener, full list of themes and codes (if helpful), longer verbatim quotes.

For a deck rather than a document, the same structure with one section per 1 to 4 slides. Findings get 1 to 3 slides each. Recommendations get 1 to 2 slides each.

---

## Quote Selection

Quotes are the evidence layer of the report. They are also the part that most reliably persuades a reader. A well-chosen quote is worth a paragraph of summary.

Principles for selecting quotes:

- **Pick quotes that illustrate the finding cleanly.** The reader should be able to read the quote and see the finding in it.
- **Two to four quotes per theme.** More than that looks padded; one quote alone is hard to weight.
- **Spread across participants.** Avoid quoting the same charismatic participant repeatedly. The pattern should be visible across the sample.
- **Attribute appropriately for the population.** For broad consumer studies, pseudonym plus a brief role or segment descriptor works: "Bilal, retail business owner, signed up 14 days ago." For B2B, specialist markets, or any small population where role plus geography could identify an individual, use "Subject A, Subject B" with a separate demographic table at the front or back of the report. (See `ethics-and-validity.md` for the full anonymization decision logic.) The rule of thumb: if you can imagine someone who knows the industry being able to identify the person from the attribution, the attribution is too revealing.
- **Avoid the "trophy quote."** The cleverest, funniest, most memorable quote may not be the most representative. Choose the quote that most accurately shows the finding, not the quote that most decorates it.
- **Use the participant's voice, not yours.** Light editing for clarity is OK. Heavy rewriting is not.

Quote-editing conventions:

- Remove fillers ("um," "you know," "like") when they do not carry meaning.
- Use brackets for short clarifying inserts. "It [the dashboard] felt cluttered."
- Use ellipses (...) for omitted material. "I tried to set up... eventually I gave up and asked my brother."
- Mark significant edits at the end of the report. "Quotes have been lightly edited for clarity; brackets indicate inserted clarifications, ellipses indicate omitted material."
- Never change the meaning. If you cannot edit the quote without changing what the participant meant, find a different quote.

---

## Language: "Many," "Some," "A Few," "One"

Qual reports do not use percentages or precise counts. The convention is rough quantifiers that signal direction without claiming precision:

- **All / most / nearly all.** Used sparingly, when the finding was nearly universal in the sample.
- **Many.** A majority of the participants spoke to the theme.
- **Some.** A substantial minority, more than two or three.
- **A few.** Two or three. Mention by characteristic.
- **One.** A single participant. Mark as a case rather than a pattern.

For B2B with small samples ("we talked to 8 enterprise architects"), it can be useful to give the actual count alongside the language. "Six of the eight architects we spoke to mentioned regulatory friction as a blocker." This is appropriate when the population is small enough that an absolute count is meaningful.

A trap to avoid: percent reporting from a qual sample. "75 percent of participants said X" is technically a number, but it misrepresents a sample of 12 as if it carried population information. It does not.

---

## Recommendations

Recommendations are the report's most-contested section. The temptation is to overclaim (recommend specific actions as if they were proven). The opposite temptation is to underclaim (so heavily hedged that nothing is recommended).

The middle path: frame recommendations as **options** or as **testable hypotheses**.

Weak recommendation:

> "We recommend redesigning the onboarding flow to include a personalized welcome video."

This is presented as a single answer, derived from qual evidence that does not actually support that specific design choice.

Stronger recommendation:

> "First-time users described the early experience as isolating. Several recovered by finding a real human inside or outside the platform. Three options follow from this:
>
> 1. Add an in-app chat prompt during the first session, with a real human or trained model on the other end. Easiest to test quickly.
>
> 2. Offer a scheduled 15-minute onboarding call within the first 72 hours, opt-in. Slower to set up, higher friction for the user.
>
> 3. Build a peer community where new users connect with experienced users in their category. Highest long-term value; requires more investment.
>
> Each option is worth quant testing or a small pilot before broader rollout. Option 1 is the lowest-risk near-term test."

The stronger version names options, links them to the evidence, acknowledges trade-offs, and gates the recommendation against future testing.

When a stakeholder asks "but which one should we do?", you can give an opinion. Mark it as opinion, not finding.

---

## The "What We Did Not Learn" Note

A short, deliberate section that flags what the study did not address. This is professional honesty and also armor against future scope creep.

Topics typically belong here:

- Segments the sample did not include
- Questions outside the project scope
- Findings that need quant validation to size
- Topics that need follow-up qual to deepen

Example:

> The study spoke to first-time users in their first 30 days post-signup. We did not include users who churned in the first 14 days; their experience may differ. We also did not include users who signed up through the reseller channel; their entry experience is reportedly different and worth a follow-on study. Findings about the value of the human moment in onboarding are directional and should be quantitatively sized before significant investment.

This section is short. Two paragraphs is plenty. It protects everyone: the buyer (who now knows the scope), the researcher (who has marked the limits), and the next project (which has a starting point).

---

## Topline vs. Full Report

A **topline** is a 1- to 3-page document delivered quickly (24 to 72 hours after fieldwork ends) summarizing the early reading. Typical structure:

- Three headline findings, one paragraph each
- One representative quote per finding
- A note on what the full report will deepen

Toplines are useful when stakeholders need a fast read to make a near-term decision. They are not full reports. Mark them clearly as "preliminary, will be deepened in the full report."

A **full report** is the deliverable from end-to-end analysis: complete, evidenced, recommended. Typical lengths:

- Light study (4 to 6 IDIs): 6 to 10 pages
- Medium study (8 to 16 IDIs or 3 to 4 focus groups): 12 to 25 pages
- Heavy study (20+ IDIs, mixed-method, B2B customer visits): 25 to 50 pages

Decks vary similarly. Keep slides to one finding or one structural element per slide. Resist the urge to put 6 quotes on a single slide; pick two and put the rest in the appendix.

---

## Common Deliverable Formats

- **Word or Google Doc.** The default for full reports. Easy to share, annotate, and print.
- **PowerPoint or Keynote.** Common for client-facing presentations. Use the deck for the in-meeting walkthrough; pair with a document for the durable record.
- **PDF.** For final, locked deliverables.
- **Findings video / sizzle reel.** A short edited video of participant quotes, organized by theme. Excellent for stakeholder buy-in. Costly to produce well. Get consent for video use upfront.
- **Insight wall / synthesis poster.** A physical or digital artifact for a workshop. Useful when the next step is a team activation session.
- **Interactive transcript explorer.** A web app where stakeholders can read transcripts, filtered by theme. Used in larger or longitudinal studies.

Match format to use case. A 40-slide deck is wasted on a CEO who wants a 1-page brief. A 1-page brief is wasted on a product team that wants to study the verbatims for their roadmap. Ask the buyer what they will do with the report.

---

## Presenting Findings Live

If the report is going to be presented in a meeting, build the meeting around the findings, not the slides.

A useful structure:

1. **Opening (5 min).** Remind the room what the question was and how the research was done. Set context.
2. **The two or three headline findings (15 to 20 min).** Walk through the most important findings, each with quotes and implications. Pause for questions after each.
3. **Supporting findings and contrasts (10 to 15 min).** The fuller picture. Move faster.
4. **Recommendations and discussion (15 to 20 min).** Frame the options. Open the floor.
5. **What we did not learn (5 min).** Set the boundaries.

Total: 50 to 65 minutes for a meaningful read-out. Less than 45 minutes and the room will not absorb. More than 75 minutes and the room will check out.

In the meeting, let the quotes do the heavy lifting. Read them aloud, slowly, in the participant's voice as much as you can. The quotes are the most memorable part of any qual presentation. Treat them with respect.

---

## Common Reporting Mistakes Beginners Make

1. **Reporting by question, not by theme.** Organizing the report around "what did people say to question 7?" produces a flat record. Organize around themes that cross questions.

2. **Burying the lede.** Putting the most important finding on page 15. Start with it.

3. **Long, indistinguishable quotes.** Three paragraph-long quotes that all say roughly the same thing. Pick the sharpest one or two.

4. **Quotes without attribution.** A quote without context (role, segment, recency) is hard to weight. Attribute.

5. **Treating the brief as the conclusion.** "The client wanted to know X. The answer is Y." This is a project closeout, not a finding. Findings cut through the brief and sometimes reframe it.

6. **Recommendations from outside the data.** A recommendation that is not anchored in something a participant said or did is the researcher's opinion, not a research finding. Mark it as such.

7. **No negative cases.** A report that only confirms the dominant pattern reads as a sales document.

8. **Counting in the report.** Percentages and absolute counts in a qual report imply more than qual can support. Use rough quantifiers.

9. **Hiding the method.** If readers cannot quickly find out who you talked to and how, they cannot assess the work. Put method front and center.

10. **No what-we-did-not-learn section.** Without it, the reader assumes the study is exhaustive. It is not.

11. **A deck designed to look impressive rather than to be read.** Heavy formatting, dense slides, busy visuals. The strongest qual decks are simple: one finding per slide, two quotes, an implication.

12. **Confusing observation with inference.** "Participants seemed frustrated" mixes observation and inference. Either quote the frustration ("'I almost gave up'") or report the inferred state and mark it as inference.

---

## A Quick Pre-Delivery Checklist

Before sending the report, run this list:

- [ ] Lead with the two or three most important findings
- [ ] Each finding has at least two participant quotes and an implication
- [ ] Method and sample are described clearly enough for a reader to assess
- [ ] No percentages or precise counts misrepresenting qual data
- [ ] Quotes are attributed (pseudonym plus role / segment / recency)
- [ ] Quote edits are marked
- [ ] Anonymization is real (no detail that could identify an individual, especially in B2B)
- [ ] Negative cases and contrasts are surfaced
- [ ] Recommendations are framed as options or testable hypotheses
- [ ] A "what we did not learn" section is present
- [ ] An executive summary that a reader could use without reading the body
- [ ] Reflexivity statement (what we expected, what surprised us) is included where appropriate
- [ ] Final read-through with fresh eyes for clarity, voice, and tone

---

## Routing Forward

After delivery:

- Archive raw data and transcripts per the ethics protocol: `ethics-and-validity.md`
- If a follow-up phase is planned, brief that work using this report as input
- If the client commissions ongoing work, consider whether a tracker, community, or pulse format fits the next phase
