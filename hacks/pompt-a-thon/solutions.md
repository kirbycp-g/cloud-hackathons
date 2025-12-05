# Prompt A Thon

## Introduction

Welcome to the coach's guide for The Pompt - a - Thon gHack. Here you will find links to specific guidance for coaches for each of the challenges.

> [!NOTE]  
> If you are a gHacks participant, this is the answer guide. Don't cheat yourself by looking at this guide during the hack!

## Coach's Guide

- Challenge 1: The Product Definition
- Challenge 2: The Market Analysis
- Challenge 3: The Board Presentation
- Challenge 4: The Regional Campaign

### Student Resources

Before the hack, it is the Coach's responsibility create and make available needed resources including:

- Files for students
  - compliance-meeting-transcript.txt
  - student-survey-data.csv
- Lecture presentation
  - #TODO

## Google Cloud Requirements

This hack requires students to have access to Google Workspace with the Gemini services enabled.

## Suggested Hack Agenda 

This is designed to fit into a 2 hour window to complete all of the challenges.

- Prompt - a -Thon
  - Challenge 1 (30 mins)
  - Challenge 2 (30 mins)
  - Challenge 3 (30 mins)
  - Challenge 4 (30 mins) 

## Repository Contents

- `README.md`
  - Student's Challenge Guide
- `solutions.md`
  - Coach's Guide and related files
- `./resources`
  - Resource files needed for challenge 1 and 2
    - compliance-meeting-transcript.txt
    - student-survey-data.csv


## Environment
This gHack uses Google Workspace and does not require any addtional Cloud resources.

## Challenge 1: The Product Definition

### Notes & Guidance

Steps:
- Open a new Google Doc. Use Gemini to ingest the compliance-meeting-transcript.txt.
- Prompt Gemini to act as a Product Manager. Ask it to draft a "Product Definition Document" that includes: Executive Summary, Target Audience (College Students), Interest Rate Structure, and Required Compliance Disclosures.
- Refinement: Use Gemini to expand the "Risk" section. Ask it to identify three potential regulatory risks mentioned in the transcript and suggest mitigation strategies for each.
- Tone Check: Highlight the Executive Summary and use Gemini to "Rephrase" it to be more "formal and reassuring" for the bank's Board of Directors.

## Challenge 2: The Market Analysis

### Notes & Guidance
- Import student-survey-data.csv into a new Google Sheet.
- Use Gemini (or Help me organize) to analyze the "Comments" column. Create a new column that categorizes feedback into: 'Interest Rates', 'Mobile App Experience', 'Fees', or 'Branch Location'.
- Prompt Gemini to create a formula or Pivot Table that counts the "Mobile App Experience" complaints vs. "Interest Rate" requests.
- Insight Generation: Ask Gemini to analyze the data and generate a clear sentence summarizing the "top requested feature" for a college student demographic.


## Challenge 3: The Board Presentation

### Notes & Guidance
- Open Google Slides. Use Gemini to create a slide outline based specifically on the "Product Definition Document" you created in Challenge 1.
- Visuals: On the "Target Audience" slide, use Gemini to generate an image of "diverse college students using a mobile banking app on a university campus, photorealistic style".
- Data Integration: Create a slide titled "Market Validation." Use Gemini to generate a bar chart description or visualization based on the Pivot Table data from Challenge 2.
- Speaker Notes: Ask Gemini to write speaker notes for the final slide that anticipates a question about "Account Security" and provides a confident answer.

> [!NOTE]  
> There is a new feature from Nano Bannana that will beautify the slide. What it does is look at a slide and creates an image of a slide that can be added to the deck. This is an image and can't be edited once added to the deck

## Challenge 4: The Regional Campaign

### Notes & Guidance

- Branch Enablement: Open a new Doc. Prompt Gemini to act as a Sales Enablement Lead. Draft a "Talking Points" script for local branch managers to use when students walk in. Ensure it highlights "No Fees" and "Mobile Check Deposit",.
- Customer Email: Open Gmail. Draft a launch email targeting "Young Professionals/Students." Prompt Gemini to reference the "Product Definition Document" to ensure the features are accurate, but set the tone to be "exciting, youthful, and financially savvy".
- A/B Testing: Ask Gemini to generate three different subject line options for the email: one focusing on "Savings," one on "Technology," and one on "Freedom".

