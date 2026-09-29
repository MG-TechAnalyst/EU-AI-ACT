You are an expert frontend developer, UX designer, and EU AI governance educational-content designer.

I need you to build a polished, professional SINGLE-FILE HTML website for an EU AI Act AI Literacy practical audit exercise.

IMPORTANT:
- Output ONLY the complete HTML code inside one ```html code block.
- Do not give explanations before or after the code.
- Everything must work by opening index.html directly in a browser.
- Use only HTML, CSS, and vanilla JavaScript.
- No React, no frameworks, no build tools, no backend.
- No external JavaScript libraries.
- Make it responsive for desktop, tablet, and mobile.
- Make it look like a real professional AI governance product, not a basic student webpage.

SOURCE / ASSIGNMENT CONTEXT

The website is based on an educational lesson about the EU AI Act and AI literacy.

The lesson covers:
1. The EU AI Act risk pyramid:
   - Unacceptable risk
   - High-risk
   - Limited-risk
   - Minimal-risk

2. Article 4 — AI literacy.

3. A five-point AI hygiene check:
   - Bias
   - Privacy
   - Consent / permission
   - Attribution / human ownership
   - Transparency

4. Example cases such as:
   - A biased CV screening system.
   - Customer information being pasted into ChatGPT.

5. The audit loop:
   - Classify
   - Check
   - Apply
   - Document

6. The practical exercise asks the learner to audit one of their own AI workflows, classify it, run the five checks, identify remediation, document the result, and optionally publish the audit to a public URL such as GitHub Pages, a Gist, Notion, or a public Google Doc.

DESIGN

Create a premium dark AI-governance dashboard.

Visual direction:
- Deep navy / almost-black background.
- Subtle technical grid.
- Cyan / electric blue accents.
- Glass-like dark cards.
- Soft gradients.
- Rounded corners.
- Professional typography.
- Strong visual hierarchy.
- Subtle hover animations.
- Minimal but impressive.
- Do not make it look like a generic Bootstrap template.
- The result should look like a startup-quality governance/audit tool.

HEADER

Create a sticky header containing:
- AI logo/icon
- "AI Literacy Audit Lab"
- Small badge: "EU AI ACT · ARTICLE 4"

HERO

Create a strong hero section with:

Small eyebrow:
"Practical AI Governance Exercise"

Main heading:
"Understand your AI.
Audit your workflow."

Supporting text explaining that the tool helps document an AI workflow, identify risks, perform the five-point hygiene check, record remediation, and demonstrate AI-literacy practice.

Add a visible privacy warning:
"Do not enter real customer names, email addresses, passwords, confidential documents or sensitive personal information."

Explain that the page performs its work locally in the browser and does not send audit information to a server.

PROGRESS INDICATOR

Create a five-step progress indicator:

1. Context
2. Workflow
3. Risk
4. Hygiene
5. Action

Update its visual state dynamically as the user fills out the audit.

ARTICLE 4 SECTION

Create a professional Article 4 information card.

Explain in plain English that Article 4 concerns AI literacy and requires providers and deployers to take measures to support the development of AI literacy among staff and other people dealing with AI systems on their behalf.

Mention that relevant technical knowledge, experience, education/training, context of use, and affected people/groups should be taken into account.

IMPORTANT:
Do not present the website's audit score as official EU legal compliance.
Clearly say that this is an educational self-audit and not legal advice.

WORKFLOW FORM

Create fields for:

- Workflow name
- AI system/tool
- Owner
- Frequency
- Information involved
- People potentially affected
- What the AI actually does

Prefill it with a realistic example:

Workflow:
"Customer support drafting with ChatGPT"

AI system:
"ChatGPT"

Owner:
"Customer-support lead"

Frequency:
"Daily"

Information:
"Customer personal data"

Affected:
"Customers"

Purpose:
"Drafts customer-support replies. A human reviews the AI-generated draft before sending it."

Allow the user to edit everything.

RISK CLASSIFICATION

Create four attractive selectable cards:

1. Unacceptable
2. High-risk
3. Limited-risk
4. Minimal

Each card should include a short educational description.

Default to Minimal for the example.

IMPORTANT:
Label this as a "Preliminary risk classification".

Add a warning that this classification is educational and does not itself determine the legal classification of an AI system under the EU AI Act.

FIVE-POINT HYGIENE CHECK

Create five interactive audit cards.

Each card must have:

- Number
- Title
- Explanation
- PASS button
- FAIL button
- N/A button
- Evidence textarea

Checks:

1. Bias
Ask whether the workflow could produce unfair or systematically different outcomes.

2. Privacy
Ask whether personal/confidential information is protected and minimised before entering the AI system.

3. Consent / permission
Ask whether relevant permission, notice, or lawful basis has been considered for information used.

4. Attribution / human ownership
Ask whether a clearly responsible person reviews and owns the final output.

5. Transparency
Ask whether people need to be informed about the AI's role in this particular workflow.

IMPORTANT:
Do NOT claim that every AI-generated email legally requires an "AI-assisted" label.
Keep transparency contextual and educational.

Default example state:

Bias:
PASS

Privacy:
FAIL

Consent / permission:
PASS

Attribution:
PASS

Transparency:
FAIL

Add realistic evidence text for each.

LIVE AUDIT DASHBOARD

Below the five checks create a live dashboard showing:

- Hygiene percentage
- Pass count
- Fail count
- N/A count
- Status such as:
  "All checks passed"
  "Mostly healthy"
  "Needs attention"

Calculate the percentage dynamically.

Do not present this score as an official EU AI Act compliance score.

REMEDIATION PLAN

Create an editable list of remediation actions.

Prefill:

1. Strip or minimise customer personal data before prompting the AI system.
2. Create clear internal guidance for staff covering approved AI use and human review.
3. Document when AI-assisted outputs require additional human review or escalation.

Allow:
- Add remediation
- Remove remediation

AI LITERACY SECTION

Add a section asking:

Training / guidance:
- None yet
- Informal guidance
- Formal AI training
- Formal training + written policy

Review frequency:
- Not scheduled
- Every 6 months
- Annually
- After material workflow changes
- Continuous governance process

Add a textarea:
"What should staff understand?"

Prefill it with a sensible description covering:
- Data handling
- AI limitations
- Human review
- Escalation
- Relevant risks

EXPORT SECTION

Create a "Generate audit.md" button.

When clicked, dynamically generate a complete Markdown audit.

The generated Markdown should contain frontmatter like:

---
workflow: customer-support-drafting-with-chatgpt
risk_tier: minimal
owner: customer-support-lead
ai_system: ChatGPT
last_audit: YYYY-MM-DD
---

Then include:

# Workflow name

## Workflow

- AI system
- Owner
- Frequency
- Information involved
- People potentially affected

### Purpose

...

## Preliminary risk classification

...

## Five-point hygiene check

bias: PASS/FAIL/N/A - evidence
privacy: PASS/FAIL/N/A - evidence
consent: PASS/FAIL/N/A - evidence
attribution: PASS/FAIL/N/A - evidence
transparency: PASS/FAIL/N/A - evidence

## Remediation

1. ...
2. ...
3. ...

## AI literacy measures

- Training / guidance
- Review frequency

### Staff should understand

...

## Audit loop

### 1. Classify
### 2. Check
### 3. Apply
### 4. Document

## Article 4 context

Explain the relevant Article 4 AI-literacy context.

## Official sources

Include official European Commission and EUR-Lex links.

## Disclaimer

"This is general education on the EU AI Act, not legal advice."

EXPORT BUTTONS

Include:

- Generate audit.md
- Copy audit
- Download audit.md
- Print / Save PDF
- Reset

The Download button must download an actual audit.md file using JavaScript Blob APIs.

The Copy button must copy the Markdown to the clipboard.

The Print button should allow browser printing / Save as PDF.

SOURCES

Use official sources:

European Commission:
https://digital-strategy.ec.europa.eu/en/policies/ai-talent-skills-and-literacy

EUR-Lex:
https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689

European Commission AI Literacy Q&A:
https://digital-strategy.ec.europa.eu/en/faqs/ai-literacy-questions-answers

Do not invent legal requirements.

PRIVACY

The site must not:
- send form data anywhere
- use analytics
- use tracking
- require login
- contain a backend

Everything should work locally in the browser.

FOOTER

Include:

"AI Literacy Audit Lab"
"EU AI Act · Article 4 · Educational self-audit"

And:

"This is general education on the EU AI Act, not legal advice."

QUALITY REQUIREMENTS

Before producing the HTML, internally check that:

- Every button works.
- Every form field works.
- Risk selection works.
- PASS / FAIL / N/A states work.
- Evidence fields are included.
- Dashboard updates dynamically.
- Remediation can be added and removed.
- Markdown generation works.
- Copy works.
- Download works.
- Print works.
- Reset works.
- Mobile layout works.
- No JavaScript errors.
- No external dependencies are required.
- The generated audit is readable Markdown.
- The website does not falsely claim legal compliance.
- The site clearly distinguishes educational guidance from legal determination.

Make the final result feel like a polished professional AI governance product that a student could confidently publish as their practical audit exercise.

OUTPUT ONLY THE COMPLETE HTML CODE.
