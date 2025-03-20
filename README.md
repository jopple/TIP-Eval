# TIP-Eval
This worksheet defines the criteria, requirements and formula for evaluating a Threat Intelligence Platform (TIP). 

Requirements Sheet (Success Criteria)

Success criteria has been divided into five sections and loosely align with the five phases of the “Intelligence Cycle” (Planning, Collection, Processing, Enrichment, Dissemination). Appendix A contains a basic, vendor agnostic, form that can be used during the evaluation process. The Planning criteria is intended to evaluate the system and resource requirements of the platform undergoing review and will be used in assessing the viability of deployment within our infrastructure. The Collection criteria will be used to assess how the platform ingests data from external sources (i.e. feeds, APIs, etc.), as well as its ability to ingest data from internal tools (i.e. firewalls, endpoint protection, etc.). The Processing criteria evaluates the platform’s method of normalizing data and the various languages/frameworks supported. The Enrichment criteria assesses a platform’s ability to automatically obtain and associate related data that could provide additional context (i.e. WHOIS, pDNS, rules etc.). The Dissemination criteria is meant to evaluate the platform’s ability to integrate with and push data to existing security appliances (i.e. firewalls, endpoint protection, IDS, etc.) found within the organization's infrastructure, as well as the organizations’s SaaS environments.

Technical Score Card

The Technical Score Card is intended to track a TIP's ability to meet the success criteria outlined in the Rrequirements Sheet. Scores are tracked for each major requirement. If a requirement consists of sub-requirements, the primary requirement's score will consit of an average of all sub-requirement scores. Scores should be 0 (does not meet requirement), 0.5 (partially meets requirement), 1 (meets requirement). 

Prior to conducting an evaluation, personnel should identify any requirements they would like to weight with a higher importance. The points cell for these requirements should be adjusted to reflect a multiple of 2 (i.e. [point value] * 2 = weighted point value. Ensure relevant point cells for all TIP columns are updated (don't just update [TIP 1])
