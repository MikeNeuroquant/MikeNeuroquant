---
title: "Validating a Mental Health Screening Tool at Scale"
excerpt: "Checked whether a widely used psychological questionnaire holds up across very different age groups, then tested how well background information alone can flag people at risk."
collection: portfolio
---

Validated a widely used psychological screening tool (DASS-42) on a public dataset of ~40,000 people. Two questions: does it measure what it claims to, and does it work the same way across groups?

It held up cleanly in young adults. In older adults the picture was more nuanced: depression items worked well, but some anxiety and stress items started to overlap, a common issue when a questionnaire is used outside its original population.

A second step asked whether background information, personality traits, and response times, without any symptom answers, could flag someone's likely risk level. Accuracy was around 60% overall, with the model especially good at catching the most severe cases, which is usually what matters most in a real screening context.

**What this shows:** the ability to validate a measurement tool properly before trusting it, and to report a model's real-world performance honestly, exactly the kind of scrutiny you'd want applied to a customer survey or employee wellbeing tool before rolling it out.

[View full project on GitHub](https://github.com/MikeNeuroquant/survey-validation-behavioral-scoring)