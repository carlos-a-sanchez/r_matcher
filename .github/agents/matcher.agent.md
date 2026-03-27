---
# Fill in the fields below to create a basic custom agent for your repository.
# The Copilot CLI can be used for local testing: https://gh.io/customagents/cli
# To make this agent available, merge this file into the default repository branch.
# For format details, see: https://gh.io/customagents/config

name: Resume Matcher 
description: Resume Matcher
tools: read
---

# My Agent


Read the data from the files:
- ./data/crm_opportunities.json

And list the content the attributes:
- opportunity_id
- client
- role_title
- seniority_required
- practice_area
- status
- urgency
- engagement_start
- duration_months
- headcount

from records as a table. 








