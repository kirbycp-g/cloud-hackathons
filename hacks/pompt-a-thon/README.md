# Prompt A Thon

## Introduction

Regional Bank executives have recently initiated discussions regarding the development of a new banking product "The Future-Fi Student Account", specifically aimed at students. This strategic focus is informed by the proximity of many bank branches to various universities and colleges. The objective is to not only acquire new clientele for the bank but also to establish long-term relationships with these students, encouraging them to remain customers following their graduation.

Your team is tasked with defining the product, analyzing survey data to either validate existing features or identify new ones, and subsequently preparing the presentation for Board approval. Finally, your team will be responsible for developing the launch materials for distribution to all bank branches.

This exercise is not centered on proficiency in document creation or typing speed. Rather, it emphasizes mastering the strategic application of the Gemini prompt. You will utilize Google Workspace Gemini AI tools to enhance your documents, spreadsheets, and presentations. The core challenge involves skillfully guiding these AI tools to produce the required final product.



## Learning Objectives

In this hack you will be solving the common business problem of creating, analyzing data and preparing communications for different audiances.

By the end of this hack, attendees will be able to:
- Use Gemini in Docs to synthesize meeting transcripts into compliance-ready project proposals.
- Use Gemini in Sheets to categorize customer sentiment and identify financial product preferences.
- Use Gemini in Slides to generate visual assets and presentations from written documentation.


## Challenges

- [Challenge 1: The Product Definition](#challenge-1-the-product-definition)
  - Create a structured Product Definition Document (PDD) from unstructured meeting notes.
- [Challenge 2: The Market Analysis](#challenge-2-the-market-analysis) 
  - Validate the product need using customer data.
- [Challenge 3: The Board Presentation](#challenge-3-the-board-presentation) 
  - Visualize the strategy for the Regional Directors.
- [Challenge 4: The Regional Campaign](#challenge-4-the-regional-campaign) 
  - Execute the launch communications.

## Prerequisites

- Basic knowledge of Google Workspace.

## Contributors

- Chris Kirby

## Challenge 1: The Product Definition

### Introduction 
Bank Executives convened a meeting to evaluate the Future-Fi Student Account, addressing key features, associated risks, and various other considerations. A comprehensive transcript of the meeting, which delineates product features, compliance risks has been produced. The objective of this effort is to formally consolidate this information into a two-page proposal, suitable for submission and presentation to the Risk Committee.

> [!NOTE]  
> Copy the Transcript here: [ComplianceMeetingTranscript](resources/compliance-meeting-transcript.txt)

### Success Criteria
- A new Google Doc titled "Product Definition Document" is created.
- The document contains four distinct sections: Executive Summary, Target Audience, Interest Rate Structure, and Compliance Disclosures, all accurately reflecting the details from the transcript.
- A "Risk Assessment" section is present, listing at least three regulatory risks and mitigation strategies derived from the transcript.


## Challenge 2: The Market Analysis

### Introduction (Optional)
Now that the initial product has been defined in Challenge 1, it is opportune to conduct market research to ascertain its potential success. Regional Bank commissioned a survey targeting students within its service area.

Leverage Gemini to analyze the "Comments" column. Following this analysis, establish an additional column to categorize the feedback into the following domains: 'Interest Rates', 'Mobile App Experience', 'Fees', or 'Branch Location'.

The analysis should be concluded by presenting a concise summary of the findings.


> [!NOTE]  
> Survey data can be found here: [StudentSurvey.csv](resources/student-survey-data.csv)

### Success Criteria
- The student-survey-data.csv file is now a Google Sheet with at least two new columns populated by Gemini: "Category" and "Sentiment".
- A summary table (Pivot Table or formula-based) exists in the sheet that quantifies the number of "Mobile App Experience" feedback items versus "Interest Rate" requests.
- Summary Statement from the data analysis


## Challenge 3: The Board Presentation 

### Introduction (Optional)
The product has been defined and initial research is complete. The next critical step is to seek approval from the board by presenting a focused pitch.

The presentation should leverage data and insights gathered from previous challenges and research phases. It must be highly concise, limited to six slides, recognizing that the board's time is valuable and limited. The core emphasis must be on the local market strategy, supported by empirical data to substantiate the approach.

When crafting the presentation, it is important to incorporate best practices for effective product vision communication, including:
- Gaining early alignment with partners, engineering, and UX teams.
- Scheduling regular leadership readouts and feedback sessions at key milestones.
- Emphasizing a clear narrative that shows and tells the story, as words alone are often insufficient.

The pitch should focus on showing how the product solves business problems and addresses unmet user needs, rather than just listing features. The objective is to secure the board's buy-in on the strategy and execution plan.


### Success Criteria

- A Google Slides deck exists containing exactly 6 slides.
- The "Target Audience" slide features a unique, AI-generated image of "college students on a university campus" (not a stock photo or clipart).
- The "Market Validation" slide contains a chart or visualization that accurately represents the data summary created in Challenge 2.


## Challenge 4: The Regional Campaign

### Introduction (Optional)
Congratulations; your team has secured approval for the new Future-Fi Student Account.

However, the team's responsibilities have not concluded. Assistance is now required for the branch offices in the launch of this new product. This effort necessitates the creation of a "talking points" script for use by branch managers and sales associates. Additionally, a draft of a sample outreach email must be prepared for dissemination to prospective student customers. To support the email marketing campaign, you are also assigned the task of generating multiple alternative email subject lines to facilitate A/B testing during the campaign.


- Develop a "Talking Points" script for local branch managers to utilize when engaging with students. This script must emphasize features identified through the analysis conducted in Challenge 2.
- Draft a product launch email directed at "Young Professionals/Students." Confirm that the features referenced are accurate by consulting the "Product Definition Document," while maintaining an engaging, contemporary, and financially informed tone.
- For A/B testing purposes, generate three distinct subject line options for the email: one emphasizing "Savings," one focusing on "Technology," and one highlighting "Freedom".


### Success Criteria
A "Branch Script" document exists, and a draft email is ready with three distinct subject line options.

