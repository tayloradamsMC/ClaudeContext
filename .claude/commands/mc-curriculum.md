---
description: Generate partner-fit subject options and a first-pass MasterClass Certificate curriculum for partner pitches
argument-hint: <partner-name> [context about the partner or their audience]
allowed-tools: [Read, WebFetch]
---

# MasterClass Certificate Curriculum Generator

You are helping generate a first-pass certificate curriculum for a partner pitch. This is a two-step process: first brainstorm subjects, then build the full curriculum after the user selects one.

## Arguments

The user invoked this command with: $ARGUMENTS

Parse this as:
- **Partner**: The first word/quoted phrase is the partner name
- **Context**: Any additional text provides context about the partner, their audience, or goals

---

## Step 1: Subject Brainstorm (Always Do This First)

Before generating any curriculum, read the pitch framing guide for context:

```
MasterClass Certificates/Curriculum Generator/pitch-framing-guide.md
```

Then generate **exactly 5 subject area options** for this partner. For each option provide:

1. **Subject Title** — The certificate name (e.g., "Financial Modeling & Valuation")
2. **Why This Partner** — 2–3 sentences: Why does this subject align with their brand authority, audience needs, and positioning? What makes a "[Partner] × MasterClass" certificate credible and desirable?
3. **Target Audience** — Who within this partner's ecosystem benefits most?
4. **Differentiation** — What makes this subject unique or timely for this partner vs. a generic provider?

Rank the 5 options from strongest to most exploratory fit.

After presenting the 5 options, ask:

> "Which of these resonates most for your pitch? Or would you like to adjust the direction — different audience, level of difficulty, or subject area? Once you pick one, I'll pull from live MasterClass certificate examples and build the full curriculum."

**Stop here and wait for the user's response before proceeding to Step 2.**

---

## Step 2: Full Curriculum Generation (After User Selects a Subject)

Once the user has selected or refined a subject, do the following:

### 2a. Fetch Live Reference Examples

Fetch these two live MasterClass certificate pages to match their tone, structure, and module format:

1. `https://www.masterclass.com/certificates/breakthrough-innovation-strategy-from-bold-idea-to-business-impact`
2. `https://www.masterclass.com/certificates/leadership-and-decision-making-under-pressure`

If either URL fails, also try:
- `https://www.masterclass.com/certificates`

Also read the local format reference for the canonical structure:
```
MasterClass Certificates/Curriculum Generator/certificate-format-reference.md
```

And read one existing certificate from the painted door doc that is closest in topic to the chosen subject:
```
MasterClass Certificates/2024 Tier 1 Certificates Copy - Painted Door Versions.md
```

### 2b. Generate the Output

Produce the full document in two sections:

---

**[PARTNER NAME] × MASTERCLASS**
**[Certificate Title]**

---

### SECTION 1: Partner Pitch Rationale

*Why [Partner] + [Subject] + MasterClass = Yes*

**The Opportunity**
2–3 sentences explaining the market moment or skill gap this certificate addresses for the partner's audience.

**Why [Partner]**
2–3 sentences on what makes this partner the right credential holder for this subject — their brand authority, their audience's relationship with this skill domain, and what a certificate "by [Partner], powered by MasterClass" signals.

**Why MasterClass**
2–3 sentences on what MasterClass uniquely brings (world-class instructors, aspirational brand, proven format) that the partner can't deliver alone.

**The Value Exchange**
- **For the partner**: What they get (brand extension, audience engagement, revenue share potential, talent pipeline, etc.)
- **For their audience**: What learners get (career advancement, credentialing, real skills)
- **For MasterClass**: What we get (new audience, brand halo, distribution)

---

### SECTION 2: Certificate Curriculum

#### Certificate 1-Liner
*One compelling sentence that captures the transformation a learner gets.*

---

#### Essential Details
1. **Shareable Certificate**: Earn a certificate you can add to your resume and LinkedIn profile.
2. **For Beginners**: No prior knowledge required.
3. **Flexible Schedule**: Complete videos & projects at your own pace.
4. **15 Hours to Complete**: 6 weeks at 2–3 hours a week.

---

#### Real Outcomes For Your Career
- [Outcome 1 — specific, measurable professional benefit]
- [Outcome 2]
- [Outcome 3]
- [Outcome 4]
- [Outcome 5]

---

#### Skills You'll Gain
[Skill 1] · [Skill 2] · [Skill 3] · [Skill 4] · [Skill 5] · [Skill 6] · [Skill 7]

---

#### Certificate Program Overview
*2–3 sentence overview paragraph describing the program's approach, who it's for, and what makes it distinctive.*

---

#### Curriculum

**Module 1: [Title]**
- **Duration**: 1 Week (2.5 hours)
- **What You'll Learn**: [1 sentence overview]
- **Videos**:
  - [Video title] (X min)
  - [Video title] (X min)
  - [Video title] (X min)
  - [Video title] (X min)
  - [Video title] (X min)
- **Activity**: [Activity name]: [Brief description] (30 min)
- **Supplemental Reading**:
  - *[Title]* (15 min)
  - *[Title]* (10 min)
- **Skills Included**: [Skill name]

*(Repeat for Modules 2–6)*

---

## Tone and Style Notes

- Match the aspirational-but-grounded tone of live MasterClass certificates
- Outcomes should be career-specific, not generic ("Develop the ability to lead cross-functional teams through ambiguity" not "Learn leadership skills")
- Module titles should be action-oriented (e.g., "Mastering the Pitch," "Building High-Performance Teams")
- The partner pitch rationale should feel like a business case memo, not marketing copy — clear logic, concrete value, confident framing
