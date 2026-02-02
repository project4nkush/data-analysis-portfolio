## Context
This project analyzes order-level data from a retail operation to understand why profitability declined despite healthy order volumes.

## Business Problem
A significant number of orders were generating negative profit, raising concerns about pricing and discounting effectiveness.

## Hypothesis
Deep discounting beyond a certain threshold may be systematically destroying profitability rather than driving sustainable volume.

## Approach
Orders were grouped into discount bands and analyzed across profit, volume, category, and sub-category dimensions using Excel pivot tables.

## Key Findings
- Profitability collapses beyond the 20–30% discount range.
- Losses are systemic but highly concentrated in a few high-volume or high-cost sub-categories.
- Uniform discounting policies fail when unit economics differ.

## Decision & Trade-offs
I would introduce category- and sub-category–specific discount guardrails and pilot gradual discount reductions.
This accepts short-term customer dissatisfaction to restore long-term margin discipline.

## What I Would Do Next
Validate findings with shipping cost and fulfillment data before rolling out policy changes at scale.

## Data Source
Dataset sourced from Kaggle (Superstore sample dataset) for learning and analysis purposes.
