# AdMind – Competitor Advertising Intelligence Engine

An AI-powered competitor advertising analysis workflow built using **n8n** for MySivi.

AdMind analyzes competitor advertisements, evaluates their creative quality, identifies messaging patterns, ranks creative samples, and generates actionable advertising concepts.

## Project Overview

The goal of AdMind is to turn competitor advertising research into structured insights that can support creative strategy and campaign planning.

The workflow processes manually collected advertisement data from the Meta Ad Library and uses AI to analyze and evaluate each creative.

## Key Features

- **Advertisement Validation:** Validates and prepares competitor advertisement data.
- **AI Creative DNA Analysis:** Analyzes hooks, messaging, persuasion, calls to action, and creative execution.
- **Creative Quality Index (CQI):** Calculates weighted creative quality scores.
- **Competitor Ranking:** Compares advertisements based on their CQI scores.
- **Strategy Analysis:** Identifies competitor messaging patterns and potential opportunities.
- **Creative Concept Generation:** Generates three proposed advertising concepts for MySivi.
- **Automated Reporting:** Generates an HTML research report that can be exported as PDF.

## Workflow Architecture

1. Research input validation
2. Advertisement normalization
3. AI-powered creative analysis
4. Explainable creative quality evaluation
5. AI scoring and CQI calculation
6. Competitor ranking
7. Competitor strategy analysis
8. MySivi creative concept generation
9. Final research report generation

## Technology Stack

- **Workflow Automation:** n8n
- **AI Integration:** OpenRouter API
- **AI Models:** Cohere North Mini Code (free model endpoint used in the workflow)
- **Research Source:** Meta Ad Library
- **Report Generation:** HTML and PDF

## Sample Research Results

Four competitor advertisements were analyzed:

| Competitor | Creative Quality Index |
|---|---:|
| Cambly | 80 |
| Hello English Online | 80 |
| Babbel | 72.8 |
| Duolingo | 55 |

These scores represent the evaluated creative samples, not actual advertising campaign performance.

## MySivi Creative Concepts

1. **Flexi-Learn Schedule** – A concept focused on flexible learning.
2. **Family-Friendly Learning** – A concept targeting parents interested in English learning for children.
3. **Smart Matching Experience** – A concept focused on personalized learning and tutor matching.

These are proposed concepts and require validation against MySivi's actual product capabilities.

## Project Deliverables

- n8n workflow JSON export
- Competitor advertising intelligence research report (PDF)
- Loom project demonstration

### Demo Video

[Watch the AdMind Project Demo](https://www.loom.com/share/f9b7e8097b74443598611bc69bcdc376)

## Research Limitations

- Advertisement data was manually collected from the Meta Ad Library.
- Some advertisement fields were unavailable or could not be verified.
- Creative Quality Index scores are based on available creative evidence.
- Scores should not be interpreted as real campaign performance metrics.
- Generated creative concepts are hypotheses, not confirmed product features.

## Purpose

This project demonstrates practical applications of AI-powered workflow automation, structured competitor research, creative evaluation, and automated reporting.

**Developed as an AI-driven advertising intelligence project.**
