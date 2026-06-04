# Optimizing Player Revival Decisions

### A Behavioral A/B Testing Case Study in Casual Gaming

A behavioral A/B testing case study focused on optimizing revive-screen strategies in casual mobile games to improve meaningful gameplay continuation, revival acceptance, and overall player engagement.

---

# Project Overview

This project is based on an experimentation scenario for the casual gaming company **“Offline Games – No Wifi Games”**. The company was experiencing a decline in revival acceptance rates and meaningful gameplay continuation after players reached the “Game Over” screen.

After analyzing the existing revive flow, it was observed that the current revive screen lacked strong visual hierarchy and behavioral guidance, making players more likely to abandon the session instead of continuing gameplay.

To address this problem, the company decided to conduct a multivariate A/B testing experiment by redesigning the revive screen.

The objective of the experiment was to identify which revive-screen strategy could improve meaningful post-revival gameplay engagement while maintaining a healthy player experience.

---

# Problem Statement

“Offline Games – No Wifi Games” was experiencing a decline in player revival acceptance rates and meaningful gameplay continuation after players reached the “Game Over” screen.

Although the game offered players an opportunity to continue gameplay through the “Save Me” option, a large portion of players were abandoning the session instead of reviving. This directly impacted:

* overall gameplay engagement,
* session continuation,
* and potential monetization opportunities through rewarded ads.

After reviewing the existing revive screen, several UX and behavioral issues were identified:

* lack of clear visual hierarchy,
* weak attention guidance toward the primary CTA,
* absence of emotional motivation,
* and no urgency or behavioral trigger encouraging continuation.

As a result, players were more likely to exit the session immediately after failure rather than continue playing.

To address this problem, the company decided to conduct a multivariate A/B testing experiment to evaluate whether behavioral design interventions could improve meaningful post-failure engagement and revival decisions.

---

# Goals

The goal of this experiment was to identify which revive-screen design could improve meaningful gameplay continuation after players reached the “Game Over” screen.

The experiment specifically aimed to:

* Increase revival acceptance rate.
* Increase average additional gameplay time per session.
* Compare the impact of:

  * visual hierarchy,
  * emotional framing,
  * and urgency-based messaging on player behavior.
* Identify whether higher revive clicks lead to meaningful engagement continuation.

The experiment also aimed to determine which variant created the best balance between:

* revive acceptance,
* gameplay continuation,
* and player experience.

---

# Methodology

## 1. Experiment Concept

The current revive screen used by “Offline Games – No Wifi Games” lacked strong visual hierarchy and behavioral guidance, causing players to abandon the session instead of continuing gameplay.

The hypothesis was that redesigning the revive screen using behavioral interventions such as visual hierarchy optimization, emotional framing, and urgency-based messaging could improve revival acceptance and increase meaningful gameplay continuation after players reached the “Game Over” screen.

---

## 2. Experiment Variants

| Variant   | Description                   |
| --------- | ----------------------------- |
| Control   | Existing revive screen        |
| Variant 1 | Visual hierarchy optimization |
| Variant 2 | Emotional framing             |
| Variant 3 | Urgency-based messaging       |

Each variant was designed to test a single behavioral intervention independently.

---

## 3. Success Metrics

| Metric Type       | Metric                                       |
| ----------------- | -------------------------------------------- |
| North Star Metric | Average Additional Gameplay Time Per Session |
| Primary Metric    | Revival Acceptance Rate                      |

---

## 4. Sample Size & Power Analysis

The experiment was conducted using a synthetic session-level dataset containing approximately **30,092 gameplay sessions** distributed across four experimental groups.

Power analysis was performed before hypothesis testing to ensure that the sample size was sufficient to detect meaningful behavioral differences between variants with statistical reliability.

---

## 5. Statistical Methodology

The following statistical techniques were used during the analysis:

### Chi-Square Test

Used to evaluate differences in revival acceptance rate across variants.

### Kruskal-Wallis Test

Used to compare gameplay continuation distributions across multiple variants since gameplay data was non-normally distributed.

### Dunn’s Post-Hoc Test

Used to identify which specific variants differed significantly after Kruskal-Wallis testing.

---

# Analysis

The experiment analysis focused on evaluating how different revive-screen strategies influenced:

* revival acceptance behavior,
* gameplay continuation,
* and overall engagement quality.

The following analyses were conducted:

* Descriptive analysis
* Funnel analysis
* Hypothesis testing
* Effect size analysis
* Variant comparison analysis

---

# Key Findings

* Variant 1 improved revive discoverability through better visual hierarchy and increased revival acceptance compared to the control group.

* Variant 2 generated the strongest meaningful gameplay continuation after revival, indicating that emotional framing created healthier engagement behavior.

* Variant 3 produced the highest revival acceptance rate, but users showed weaker gameplay continuation quality compared to Variant 2.

* The findings demonstrated that the variant generating the highest immediate conversion was not necessarily the variant producing the healthiest long-term engagement.

---

# Final Recommendation

Based on the experimental findings, **Variant 2 (Emotional Framing)** was identified as the most effective revive-screen strategy.

Although Variant 3 generated the highest revive clicks, Variant 2 produced stronger meaningful gameplay continuation and healthier engagement quality after revival.

The final recommendation was to prioritize behavioral strategies that improve long-term player engagement rather than optimizing only for short-term revive conversions.

