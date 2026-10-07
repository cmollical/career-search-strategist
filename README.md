# Career Search Strategist

A reusable Agent Skill for experienced professionals who want to make a deliberate career move with greater level, scope, compensation, or all three.

This package turns a job search into an evidence-based operating system instead of a high-volume application exercise.

## What it does

The skill can help a user:

- establish a career baseline from resumes, LinkedIn profiles, performance reviews, compensation documents, interview notes, and project summaries
- define the move they are actually trying to make
- build a credible career narrative
- create an updated core resume that becomes the factual base for tailored application resumes
- align the user's LinkedIn profile with that core resume and, with approval, update supported LinkedIn fields through the browser
- identify primary, stretch, adjacent, and avoid role lanes
- turn those lanes into tailored natural-language job searches for LinkedIn and similar platforms
- establish compensation guardrails
- mine career evidence and build an interview story bank
- identify target companies and networking strategies
- evaluate live opportunities with a weighted scorecard
- tailor resumes without inventing experience
- prepare for interviews
- draft networking and hiring-manager outreach
- compare and negotiate offers
- maintain an active search pipeline and weekly operating cadence

## Package structure

```text
career-search-strategist/
├── SKILL.md
├── README.md
├── references/
│   ├── methodology.md
│   ├── career-discovery-interview.md
│   ├── evidence-and-story-mining.md
│   ├── compensation.md
│   ├── opportunity-scoring.md
│   ├── outreach-and-networking.md
│   └── privacy.md
└── templates/
    ├── PROFILE.md
    ├── CORE_RESUME.md
    ├── LINKEDIN_PROFILE.md
    ├── SEARCH_STRATEGY.md
    ├── CAREER_NARRATIVE.md
    ├── EVIDENCE_LEDGER.md
    ├── COMP_GUARDRAILS.md
    ├── TARGET_COMPANIES.md
    ├── LINKEDIN_SEARCH_PLAN.md
    ├── NETWORK.md
    ├── SEARCH_STATE.md
    ├── DECISION_SCORECARD.md
    ├── STORIES/STORY_TEMPLATE.md
    ├── OPPORTUNITIES/OPPORTUNITY_TEMPLATE.md
    ├── INTERVIEW_PREP/INTERVIEW_TEMPLATE.md
    └── OUTREACH/OUTREACH_LOG.md
```

## Getting started

Open this folder in Codex or another AI workspace, then give the agent the career materials you are comfortable sharing. If the product does not automatically discover the skill, ask it to read `SKILL.md` before it begins.

A strong starting set is:

1. current resume
2. LinkedIn profile or exported profile
3. one or more recent performance reviews
4. notes containing major accomplishments and metrics
5. current compensation information, only if you want compensation strategy
6. any job descriptions that represent the kind of move you want

Then say something like:

> Read `SKILL.md` and build my career-search strategy from these materials. Start by extracting the evidence and identifying the level and scope I have already demonstrated. Share your initial assessment, then interview me in focused rounds to uncover important accomplishments, scope, preferences, or career possibilities that the documents do not capture. Use the combined evidence to create an updated core resume, align my LinkedIn profile with it, define my primary, stretch, adjacent, and avoid role lanes, and create tailored LinkedIn searches. Use the core resume as the factual base for future tailored application resumes. Ask questions that could materially improve the strategy rather than repeating information already in my documents. Draft and show me any LinkedIn changes before asking for permission to update my live profile through the browser.

The skill should do as much extraction as possible before asking questions.

## Recommended kickoff workflow

For a new search, the agent should help the user move through this loop:

1. Review the resume, LinkedIn profile, performance reviews, interview notes, and other source material.
2. Share an initial assessment of the user's demonstrated level, strongest evidence, recurring themes, and important unknowns.
3. Interview the user in focused rounds to uncover missing scope, accomplishments, metrics, preferences, and work they want more or less of.
4. Turn the combined documentary evidence and interview findings into a current core resume, a factually aligned LinkedIn profile draft, a career narrative, and primary, stretch, adjacent, and avoid role lanes.
5. Write tailored natural-language searches for LinkedIn or other job platforms, including role themes, example titles, industries, seniority, work model, location constraints, and important exclusions.
6. Recommend a small set of saved searches and alerts. For an active search, prioritize newly posted roles, including a past-24-hours view when the platform supports it.
7. Review promising job links the user shares and recommend **pursue**, **explore**, or **pass**.
8. For roles worth pursuing, verify the opening on the employer's official careers site, tailor the resume without changing facts, and recommend applying through the official site when available.
9. Track the opportunity, next action, and search learnings so the strategy improves over time.

The search language should be derived from the user's evidence rather than copied from a single current title. It can include both recognizable job titles and descriptions of the problems, operating scope, and transformation work the user wants to own.

## Example requests

You can use normal language. Examples:

> Evaluate this Director role and tell me whether it is actually a good next move.

> Tailor my resume for this posting without changing any facts.

> Build my core resume from the verified evidence, then use it as the source for future tailored resumes.

> Compare my core resume and LinkedIn draft, show me the proposed LinkedIn changes, and—after I approve them—use the browser to update only those fields on my signed-in profile.

> Prepare me for my recruiter screen tomorrow.

> Build my compensation guardrails.

> Turn my performance reviews into an evidence ledger and interview story bank.

> Interview me about my career after reviewing my materials. Help me uncover what my resume is missing, improve my LinkedIn positioning, and determine what work I should pursue next.

> Help me identify the companies and leaders I should be networking with.

> Create the natural-language LinkedIn searches and filters I should use for my primary, stretch, and adjacent role lanes.

> Review this LinkedIn job link, verify it on the company website, and tell me whether I should apply.

> Compare these two offers based on level, scope, dependable cash, and long-term trajectory.

> Review my active search and tell me the five highest-value things to do this week.

## Recommended first session

For a new user, the most useful sequence is:

**Evidence → Career interview → Core resume and LinkedIn → Move → Narrative → Target lanes → Compensation → Access strategy → Search execution**

Do not start by spraying job listings at the user.

## Privacy

Career materials can contain sensitive information. Review `references/privacy.md` before sharing generated artifacts publicly.

The templates intentionally contain no personal information.

## Customization

The weights, compensation philosophy, weekly cadence, target lanes, and workspace structure are defaults. The user's explicit goals and constraints always take precedence.

## Design philosophy

This skill was built around a simple idea:

**A strong senior-level job search is not primarily an application problem. It is a positioning, evidence, access, and decision-quality problem.**

The system should help the candidate understand what they have already proven, translate that proof into the market, create access to the right opportunities, and avoid moves that look attractive but fail the actual career objective.
