# TIP-Eval
This worksheet defines the criteria, requirements and formula for evaluating a Threat Intelligence Platform (TIP). 

Requirements Sheet (Success Criteria)

The success criteria are divided into five sections, aligning loosely with the five phases of the Intelligence Cycle: Planning, Collection, Processing, Enrichment, and Dissemination.

- Planning evaluates the system and resource requirements of the platform under review, helping assess its viability for deployment within our infrastructure.
- Collection assesses the platform’s ability to ingest data from external sources (e.g., feeds, APIs) and internal tools (e.g., firewalls, endpoint protection).
- Processing examines how the platform normalizes data, including the languages and frameworks it supports.
- Enrichment measures the platform’s capability to automatically retrieve and associate relevant contextual data (e.g., WHOIS, passive DNS, rules).
- Dissemination evaluates the platform’s ability to integrate with and push data to existing security appliances (e.g., firewalls, endpoint protection, IDS) and the organization's SaaS environments.

Technical Score Card

The Technical Scorecard is designed to evaluate a Threat Intelligence Platform's (TIP) ability to meet the success criteria outlined in the Requirements Sheet. Each major requirement is assigned a score, and if a requirement has sub-requirements, its overall score is calculated as the average of all sub-requirement scores.

Scoring follows a standardized scale:

- 0: Does not meet the requirement
- 0.5: Partially meets the requirement
- 1: Fully meets the requirement

Before conducting an evaluation, personnel should determine if any requirements warrant a higher weighting. For these, adjust the points cell by applying a multiplier of 2 (i.e., [point value] * 2 = weighted point value). Ensure that the adjustments are applied consistently across all TIP columns, not just for a single TIP (e.g., do not update only [TIP 1]).
