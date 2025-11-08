# Prompt Iteration: AICPA AI Positioning

## Context

Testing how Claude vs GPT respond to the same prompt, and exploring how to refine prompts to get at the actual question.

---

## Iteration 1

### Sara's Question

This morning I've been thinking about the differences between yours and GPT's responses. For example, I was asking myself the question:

> "What has the AICPA been lobbying for as it relates to AI?"

I'm curious if they advocate more for the professionals or more for the technology.

In the folder "A vs B", I gave you and GPT the same prompt to see what would happen.

**Questions:**
1. Do you understand what I'm curious about?
2. If so, how might you improve the prompt I sent?

### Original Prompt (v1)

> I'm a CPA & will be giving a seminar on AI to our firm. We have about 15 partners and 15 staff accountants (plus about 15 other staff). I'm thinking about AICPA guidance, lobbying efforts & other messaging on AI, and how they may have changed from 2023 to today. Will you please assemble some source material in a timeline format for me to review?

---

### Claude's Analysis

**What Sara is actually curious about:**
- Whether the AICPA (the professional organization that's supposed to represent CPAs) is advocating for professionals maintaining judgment and control, OR if they're pushing toward automation/AI replacement
- Whether there might be financial/political ties influencing their position
- This connects to Sara's work on Constitutional AI vs dependency models

**Gap between prompt and intent:**

The prompt asks for a **timeline of AICPA messaging**, but what Sara actually wants to know is:
- **Which direction are they pushing?** (Pro-human judgment vs pro-automation)
- **Why might they be pushing that way?** (Financial ties, tech company influence, etc.)
- **Has their position shifted?** (And if so, what caused the shift)

---

### Improved Prompt (v2)

```
I'm a CPA preparing an AI seminar for my firm. I'm researching how the AICPA
has positioned AI to the profession, particularly whether they're advocating
for AI as a tool that enhances professional judgment or as automation that
replaces professional tasks.

Please help me analyze:

1. AICPA's public messaging on AI from 2023 to present - how have they framed
   AI's role in the profession? What language do they use?

2. Any lobbying positions, policy recommendations, or regulatory guidance
   they've issued - do these favor professional control or automation?

3. Financial or organizational ties between AICPA and AI technology companies
   - partnerships, sponsorships, board connections, etc.

4. Whether their messaging has shifted over this period - and if so, what
   might explain the shift?

I'm particularly interested in whether AICPA is advocating for professionals
maintaining judgment and control (constitutional AI approach) versus promoting
efficiency/automation models that could lead to skill atrophy or liability issues.

Please cite specific sources so I can verify.
```

---

### Key Changes

**v1 → v2 improvements:**

| Aspect | Original (v1) | Improved (v2) |
|--------|---------------|---------------|
| **Format request** | Timeline | Analysis of position/direction |
| **Clarity of intent** | Implicit | Explicit (pro-judgment vs pro-automation) |
| **Depth** | Compilation | Analysis with specific angles |
| **Verification** | Not mentioned | "Cite sources so I can verify" |
| **Context** | Basic | Connects to constitutional AI framework |
| **Specific questions** | Vague "messaging" | 4 specific analytical questions |

---

## Teaching Value

This iteration demonstrates:
- **Description (4D Framework)**: Gap between literal ask and actual intent
- **Discernment**: Recognizing when responses don't answer your real question
- **The refinement loop**: Description → Discernment → Refined Description
- **Constitutional AI behavior**: Claude asked clarifying questions rather than just executing the literal request
- **Professional thinking**: CPAs do this all the time - ask, evaluate, reframe

---

## Next Steps

- [ ] Test v2 prompt with both Claude and GPT
- [ ] Compare responses to v1 vs v2
- [ ] Document what makes v2 more effective
- [ ] Consider using this as seminar example

---

## Meta Notes

**For seminar use:**
- This is an authentic, real example (not contrived)
- Shows practical skill development
- Demonstrates AI tool differences
- Illustrates iterative professional inquiry
