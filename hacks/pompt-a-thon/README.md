# Prompt A Thon

## Introduction

Welcome to the "Regional Launch" hack. You and your team are part of the Product & Marketing squad at a Regional Bank. Executive leadership has just green-lit a new product: "The Future-Fi Student Account," a high-yield savings/checking hybrid aimed at college students.

You have a raw transcript from a compliance and product meeting, and a CSV file of customer survey data. Your goal is to use Gemini for Google Workspace to build the strategy, analyze the risk, create the pitch deck, and launch the marketing campaign—all while adhering to strict banking brand guidelines.

## Learning Objectives

In this hack you will be solving the common business problem that companies in the mineral extraction industry face and how IoT solutions from Google are brought to bear.

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
A transcript has been provided from the Product Vice President, which detailed features, compliance risks, and timelines over the course of an hour. The objective is to condense this information into a formal, two-page proposal suitable for presentation to the risk committee.

> [!NOTE]  
> Copy the Transcript here: [ComplianceMeetingTranscript](resources/compliance-meeting-transcript.txt)

### Success Criteria
- A new Google Doc titled "Product Definition Document" is created.
- The document contains four distinct sections: Executive Summary, Target Audience, Interest Rate Structure, and Compliance Disclosures, all accurately reflecting the details from the transcript.
- A "Risk Assessment" section is present, listing at least three regulatory risks and mitigation strategies derived from the transcript.


## Challenge 2: The Market Analysis

### Introduction (Optional)
Validate the necessity of the product using customer data.

Following the definition of the new product, a survey was administered to students at a local university. This data must be leveraged to substantiate the demand for this product.

Utilize Gemini (or the "Help me organize" feature) to analyze the "Comments" column. Subsequently, create a new column to categorize feedback into the following domains: 'Interest Rates', 'Mobile App Experience', 'Fees', or 'Branch Location'.

Conclude by summarizing the findings in a succinct statement.

> [!NOTE]  
> Survey data can be found here: [StudentSurvey.csv](resources/student-survey-data.csv)

### Success Criteria
- The student-survey-data.csv file is now a Google Sheet with at least two new columns populated by Gemini: "Category" and "Sentiment".
- A summary table (Pivot Table or formula-based) exists in the sheet that quantifies the number of "Mobile App Experience" feedback items versus "Interest Rate" requests.
- Summary Statement from the data analysis


## Challenge 3: The Board Presentation 

### Introduction (Optional)
Upon the completion of the product definition and comprehensive market analysis, it is now necessary to prepare the presentation for the board of directors. This presentation must consist of six slides, emphasizing the local market strategy supported by empirical data.

### Success Criteria

- A Google Slides deck exists containing exactly 6 slides.
- The "Target Audience" slide features a unique, AI-generated image of "college students on a university campus" (not a stock photo or clipart).
- The "Market Validation" slide contains a chart or visualization that accurately represents the data summary created in Challenge 2.


## Challenge 4: The Regional Campaign

### Introduction (Optional)
The product has received approval. The next steps involve preparing local branch managers and initiating customer communication via email.

- Develop a "Talking Points" script for local branch managers to utilize when engaging with students. This script must emphasize features identified through the analysis conducted in Challenge 2.
- Draft a product launch email directed at "Young Professionals/Students." Confirm that the features referenced are accurate by consulting the "Product Definition Document," while maintaining an engaging, contemporary, and financially informed tone.
- For A/B testing purposes, generate three distinct subject line options for the email: one emphasizing "Savings," one focusing on "Technology," and one highlighting "Freedom".


### Success Criteria
A "Branch Script" document exists, and a draft email is ready with three distinct subject line options.

