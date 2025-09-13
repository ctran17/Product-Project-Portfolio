# Improving Continuity on Instagram: Resume & Recently Viewed

## Introduction
Instagram is optimized for fresh discovery, but when users leave mid-Reel/post and return, the app often refreshes and loses their place. This case study proposes a lightweight continuity layer that reduces frustration and increases completion/engagement without cluttering the UI.

## Why Now
Reels now account for ~60% of time spent on Instagram. Losing continuity directly disrupts that core engagement loop, creating friction at the heart of Instagram’s fastest-growing format. Fixing this now directly supports Instagram’s engagement and ad-revenue priorities.

## Problem Statement
Users commonly exit the app mid-scroll; on reopen, the session resets, making it hard to find the last Reel/post. This disrupts continuity, wastes time, and can reduce completion and satisfaction.

## Target User Personas
- Busy Professional (25): “I scroll during breaks, and when I come back, I lose the Reel I was halfway through.”
- Casual Dipper (30): “Sometimes I check IG for 2 minutes, so I don’t want to hunt for where I left off.”
- Reel Power User (19): “If I get interrupted, it’s annoying to re-find the Reel. TikTok keeps me more locked in.”

## Goals & Success Metrics
- **+15%** Reel completion rate  
- **+10%** average session duration  
- Fewer “lost content” complaints (qualitative survey/social sentiment)
- **Business tie-in:** higher completion → more ad impressions delivered → incremental revenue

## Proposed Solution
1) **Resume Toast** on reopen:  
   - “Continue watching?” + title snippet + **Resume** / **Dismiss**  
   - Appears once per session; can be dismissed by swiping the feature away; small “Resumed” chip when used.
2) **Recently Viewed** (optional):  
   - Profile → Saved → Recently Viewed (opt-in, last 7 days)  
   - Row: thumbnail, creator, snippet, viewed-time, Resume chevron.

## Competitive Scan (summary)
- **YouTube:** robust watch history + resume; sets expectation for continuity.  
- **TikTok:** varied reopen behavior; less explicit resume.  
- **Twitter/X:** “In case you missed it” aids session continuity.

## Constraints & Trade-offs
- **Privacy:** Users may not want a persistent history.  
  - *Mitigation:* history is **opt-in**, easy clear, off by default.  
- **Freshness:** Old content could crowd out new.  
  - *Mitigation:* limit to 10 items/7 days; toast once per session.  
- **Simplicity:** Avoid UI clutter.  
  - *Mitigation:* toast is ephemeral; history tucked under Saved or inside Your activity.

## Success Criteria & Experiment
- **A/B test**: control vs. toast; secondary variant adds history.  
- **Primary:** Reel completion + session duration  
- **Guardrails:** No drop in new-content impressions, no spike in app relaunch latency  
- **Qual:** in-app survey: “It’s easier to continue what I was watching.” (Agree %)

**Iteration & Risk Plan:**
- If neutral results → iterate on placement/timing of toast.
- If negative (e.g., reduced discovery) → limit feature to opt-in Recently Viewed only.
- Rollout: internal → small market test → full scale.

## Mockups
### Low-to-Mid-Fidelity Prototype
[View the clickable lo-fi prototype in Figma](https://www.figma.com/make/Hj4xMGy5KGF8qUfDswd6qT/Lofi-Instagram-Prototype?node-id=0-1&t=Ui4FY4i08L1SuKKV-1)

Note: best experienced with iPhone 16 layout option in Figma

### High Fidelity Prototype
Coming soon from Figma :)

## Future Extensions
- Personalized Resume: ML surfaces only high-likelihood-to-complete content.
- Cross-device sync: start on mobile, resume on web/desktop.
- Deeper analytics for creators: track “resume completions” as a new metric.

## Vision & Impact
This adds continuity without undermining Instagram’s fresh-first model—reducing frustration and nudging more completes with minimal UI surface area. Continuity transforms Instagram from a place of quick dips into a space of sustained engagement. By bridging the gap between discovery and completion, we keep users immersed in what they love — while unlocking more opportunities for creators and Instagram’s business alike.
