# ResumeOps

A systems-based job search workflow using AI-assisted resume tailoring, structured analysis, and repeatable processes. Built for experienced professionals targeting $100K+ roles in GRC, compliance, privacy, AI governance, and adjacent fields -- but the methodology works for any domain.

## What's in Here

### `Resume_Tailoring_Prompt.md`

A reusable system prompt you paste into any LLM conversation. Drop in a job description and get back:

- **Analysis**: JD parsing, match ratings (STRONG / PARTIAL / GAP), killer angles, gap strategy
- **Tailored Resume**: Full resume text with JD-mirrored vocabulary, quantified accomplishments, and strategic reframing
- **Cover Letter**: Three-paragraph structure (Hook, Proof, Business Close), under 250 words, with a hierarchical addressing system for finding the right recipient

The prompt includes a candidate source materials section where you fill in your experience inventory once. It pulls from that inventory to build every resume, selecting what serves each specific JD.

#### Key features baked into the prompt:

- **Honesty guardrails**: Reframe and emphasize existing experience only. Never fabricate.
- **ATS optimization**: Mirrors JD vocabulary so automated screening catches the matches.
- **Age-proofing**: Configurable career span language. No graduation years. Forward-arc framing.
- **IC positioning**: Configurable for individual contributor vs. management targeting.
- **Cover letter addressing hierarchy**: Hiring manager by name > budget owner by title > internal recruiter > specific title without name. Never "Dear Hiring Manager."

### `Job_Search_Workbook_Template.xlsx`

An Excel workbook with pre-built tabs for tracking your entire job search:

- **Applications Pipeline**: Company, role, comp, fit rating, salutation, status (dropdown), applied date, callback tracking, notes
- **Network & Referrals**: Contact tracking with name, title, LinkedIn URL, email, relationship, relevance, confidence rating, outreach status
- **JD Summary**: Consolidated view of all roles with killer angles, key gaps, and links to detailed analysis files
- **Cross-Role Skills Map**: Heat map with your target roles as rows and skill areas as columns. Color-coded STRONG / PARTIAL / GAP ratings to spot patterns across your pipeline.
- **Source Inventory**: Track which materials you have loaded (resumes, LinkedIn, etc.) and their status

## Workflow

```
1. Fill in the prompt's Source Materials section with your experience inventory
2. Find a job posting
3. Paste the prompt + JD into a new LLM conversation (or Cowork/similar autonomous tool)
4. Get back: analysis + tailored resume + cover letter
5. Log the role in the workbook
6. Research contacts at the company, log in Network & Referrals
7. Rate the role in the Cross-Role Skills Map
8. Submit: upload tailored resume, paste cover letter, track status
9. Repeat
```

### Scaling with Cowork or Autonomous Agents

The prompt is designed for batch processing. If you use an autonomous tool like Claude's Cowork, you can hand it the prompt + a JD and get back a complete package (analysis .xlsx + tailored resume .docx + cover letter .md) without message-by-message interaction. One JD per task for best quality.

### Pairing with Autofill Tools

Tools like Simplify Copilot (free tier) handle the form-filling drudgery on Workday, Greenhouse, Lever, etc. Set up your profile once with static info (contact, education, certifications, work history), then attach the tailored resume manually per application. The autofill handles the repeated fields; you handle the strategy.

## Customization

The prompt is domain-configured for GRC / compliance / privacy / AI governance, but the methodology is universal. To adapt it for your field:

1. Replace the Source Materials section with your own experience inventory
2. Update the Areas of Expertise categories to match your domain's taxonomy
3. Adjust the cover letter's "quantifiable metrics" guidance to reflect how success is measured in your field (revenue, scale, outcomes, publications, etc.)
4. Modify the age-proofing rules to match your preference
5. Update the workbook's skills map column headers to reflect your key skill areas

## What This Doesn't Do

- **Auto-apply**: This is a strategy and tailoring toolkit, not a mass-application bot. Every resume is different because every JD is different.
- **Fabricate experience**: The prompt explicitly prohibits inventing experience, inflating scope, or claiming skills you don't have. It reframes and emphasizes what's real.
- **Replace judgment**: The gap analysis tells you where you're strong and where you're not. You decide whether to apply, how to address gaps, and when to walk away.

## License

MIT. Use it however you want.

## Acknowledgments

Built during an actual job search sprint. The methodology was developed iteratively through real applications and refined based on what worked.
