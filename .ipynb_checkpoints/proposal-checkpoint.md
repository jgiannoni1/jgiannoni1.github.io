---
layout: page
title: Project Proposal
---

# Project Proposal – Web Scraper Optimization
**Author:** James Giannoni

## Vision Statement
Optimize my existing real estate web scraper (Python / Selenium) through:
- The addition of concurrent futures, proxy rotation, better fallback mechanisms, headless/server hosting with cron job scheduling, and randomized timings to imitate human interaction.
- Utilizing a Large Language Model (LLM) once a target page (property appraisal) has been reached to scrape the required data, regardless of how it is formatted.

## Motivation
- I already use the current iteration of my web scraper, but it breaks easily, runs locally, takes multiple hours to complete, and does not take sufficient precautions against detection or failure.
- Because property appraisal pages vary widely in structure and formatting, I am unable to scrape them directly and instead rely on a workaround that is not cost-effective in the long term.
- Optimizing my scraper in the ways described above should address these issues, saving both time and money.
- I am professionally positioned within the real estate space, and a project like this will benefit both myself and others in my professional network.

## Risks to Project Completion
- Uncertainty around cost implications for:
  - The LLM models under consideration, particularly with respect to the volume of pages scraped.
  - Proxy rotation (paid services vs. free solutions, and their respective tradeoffs).
  - Server infrastructure and potential storage (e.g., AWS EC2, S3).
- The overall scope of the optimization may be too large to complete fully within a single semester.

## Mitigation Strategy
- Identify LLM models that perform well while remaining cost-effective at the target scraping volume by:
  - Estimating average monthly page counts.
  - Evaluating rate limits and price-per-token models.
- Be meticulous and agile in planning by:
  - Creating a Trello board.
  - Defining a clear Minimum Viable Product (MVP).
  - Prioritizing core functionality before optional enhancements.

## Project Assessments
Once the project is complete, the scraper should:
- Scrape data using an LLM with minimal hallucination and at least **85% accuracy**.
- Run successfully from a **server environment**.
- Utilize **proxy rotation**.
- Scrape all target pages in **under 60 minutes**.
