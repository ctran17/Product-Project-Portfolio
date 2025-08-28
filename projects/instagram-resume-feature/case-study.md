# Improving Continuity on Instagram: Resume & Recently Viewed

## Introduction
Instagram is optimized for fresh discovery, but when users leave mid-Reel/post and return, the app often refreshes and loses their place. This case study proposes a lightweight continuity layer that reduces frustration and increases completion/engagement without cluttering the UI.

## Problem Statement
Users commonly exit the app mid-scroll; on reopen, the session resets, making it hard to find the last Reel/post. This disrupts continuity, wastes time, and can reduce completion and satisfaction.

## Goals & Success Metrics
- **+15%** Reel completion rate  
- **+10%** average session duration  
- Fewer “lost content” complaints (qualitative survey/social sentiment)

## Target Users
- Casual/busy users who dip in and out  
- Reel bingers who often get interrupted  
- Power users who want a quick way to pick up where they left off

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

## Mockups
Coming soon from Figma :)

## Impact
This adds continuity without undermining Instagram’s fresh-first model—reducing frustration and nudging more completes with minimal UI surface area.
