# Markdown Buddy – R Data Analysis Project

**Student:** Rajveer Kaur  
**Course:** BDA400 – Data Science Tools and Techniques  
**Assignment:** Assignment 1 – Markdown Buddy: Use ChatGPT to Draft and Format R Docs  

> **AI Assistance Declaration:** I used ChatGPT (GPT-5.6 Sol) on October 5, 2026, for assistance with README structure, Markdown formatting, organization, and documentation suggestions. Prompts used included requests to identify appropriate README sections, improve Markdown organization, and review syntax for readability. I manually reviewed the generated content and verified the Markdown structure through GitHub preview. No real or personal dataset was uploaded to the AI tool. All final work was reviewed by me, and I am responsible for its accuracy and originality.

## Overview

This repository was created for BDA400 Assignment 1 to demonstrate professional documentation practices for an R data analysis project.

The project focuses on organizing an R analysis workflow and documenting it using Markdown and R Markdown. The repository demonstrates how clear documentation can help other users understand a project's purpose, requirements, inputs, outputs, and basic workflow.

## Project Objectives

The main objectives of this project are to:

- Create a clear and professional GitHub README.
- Apply correct Markdown syntax and formatting.
- Document an R script using R Markdown.
- Organize project information using meaningful headers and sections.
- Use code blocks with appropriate syntax highlighting.
- Validate documentation using GitHub and R Markdown preview tools.
- Demonstrate responsible and transparent use of AI assistance.

## Repository Structure

```text
markdown-buddy-rajveer-kaur/
├── README.md
├── analysis_documentation.Rmd
├── Reflection.md
└── Appendix.md
```

### File Descriptions

- **README.md** – Provides an overview of the project, setup instructions, example code, verification information, and AI assistance disclosure.
- **analysis_documentation.Rmd** – Documents the purpose, inputs, processing steps, and outputs of an R analysis script.
- **Reflection.md** – Contains reflections on the documentation and AI-assisted workflow.
- **Appendix.md** – Records the prompts used with ChatGPT and summarizes key AI-assisted responses.

## Requirements

The project can be reviewed using:

- R
- RStudio or Posit Cloud
- GitHub
- R Markdown
- A Markdown-compatible preview tool

## Installation

Clone the repository from GitHub or download the repository files.

If required, install the R Markdown package in R:

```r
install.packages("rmarkdown")
```

Load any required packages before running the analysis.

```r
library(rmarkdown)
```

## Example Code

The following example demonstrates a simple workflow using a synthetic dataset in R:

```r
sample_data <- data.frame(
  category = c("A", "B", "C"),
  value = c(12, 18, 15)
)

summary(sample_data)
```

This example uses synthetic values only and does not contain personal or confidential information.

## Documentation Approach

The documentation uses standard Markdown features, including:

- Headers
- Bullet lists
- Bold text
- Inline code
- Fenced code blocks
- R syntax highlighting
- Clearly separated project sections

These features make the repository easier to read, maintain, and navigate.

## Verification and Refinement

The documentation was manually reviewed after the AI-assisted draft was created.

The following verification steps were used:

1. Reviewed the README structure against common GitHub README practices.
2. Checked Markdown headers, lists, code fences, and spacing.
3. Used GitHub Preview to confirm that the Markdown rendered correctly.
4. Reviewed the R Markdown organization for consistent headings and code chunks.
5. Performed a self spot-check for readability, spelling, and unnecessary content.

### Improvements Made After Review

Two main improvements were made during refinement:

- The README was reorganized into shorter sections so project information could be located more easily.
- File descriptions and verification information were added to make the purpose of each project component clearer.

## License

This repository was created for educational purposes as part of BDA400 – Data Science Tools and Techniques.

## AI Assistance Disclosure

**AI Tool Used:** ChatGPT (GPT-5.6 Sol)  
**Date Used:** October 5, 2026

### Main Prompts

1. "Explain what sections a good GitHub README for an R data analysis project should include."
2. "Revise the sections list so it’s concise and uses Markdown headers and bullet formatting."
3. "Check the Markdown syntax for correctness and readability."
4. "Generate a professional README.md file using Markdown."
5. "Add sections for Installation, Example Code, and License. Keep tone concise and professional."
6. "Review the Markdown for syntax errors and suggest 2 improvements for clarity."

### Changes Made After AI Assistance

The AI-assisted content was manually reviewed and refined. I checked the organization, Markdown syntax, headings, lists, code blocks, and readability. I also ensured that only synthetic example data was included and that the final repository documentation matched the assignment requirements.

The final documentation was reviewed by me before submission.
