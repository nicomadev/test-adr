# [0001] Use an Architecture Decision Record (ADR) of plain markdown files in a repository

![2023-06-17](https://img.shields.io/badge/date-2023--06--17-F5F5DC?style=flat-square)
![Accepted](https://img.shields.io/badge/status-accepted-brightgreen?style=flat-square)

<!--

![Draft](https://img.shields.io/badge/status-draft-lightgrey?style=flat-square)
![Proposed](https://img.shields.io/badge/status-proposed-blue?style=flat-square)
![Accepted](https://img.shields.io/badge/status-accepted-brightgreen?style=flat-square)
![Rejected](https://img.shields.io/badge/status-rejected-red?style=flat-square)
![Deprecated](https://img.shields.io/badge/status-deprecated-orange?style=flat-square)
[![Superseded by ADR-aaaa](https://img.shields.io/badge/status-superseded%20by%20ADR--aaaa-yellow?style=flat-square)](aaaa-example.md)

-->

Deciders: [Nicolas Maurice](https://github.com/nicomadev) (team member)

## Context

Regarding important choices impacting our software development, we want to:

1. Induce team members to really think about them
2. Keep track of past decisions and why they were made to:
   - Remember why decisions were made considering the available options at the time and easily assess if they are still relevant
   - Provide information to new team members that were not involved in past decisions

NB: the company requires us to use GitHub as our versioning tools, so this ADR falls within this framework.

### Criteria

- Ease of use
  - Very low learning curve
  - Easy to write, maintain and read
- Vendor independence
- Versioning
- Tool/platform/service actively maintained
- Can be private

### Considered Options

- GitBook
  - Nice look and feel (navigation side bar, colors)
  - Can sync with GitHub repo to edit locally
  - Additional cost of $6.70/user/month
- Plain markdown files in a GitHub repository
  - No additional cost
  - Basic navigation sidebar in GitHub code tab
- Markdown files in a Jekyll site hosted in GitHub Pages
  - Nice look and feel (customizable theme)
  - No additional cost
  - Requires GitHub action to publish
  - Requires Ruby to test locally

Some options were outright excluded:

- Confluence and similar tools because they are vendor dependent
- GitHub wiki because of the missing versioning feature

## Decision

We will use plain markdown files in a GitHub repository, because:

- it meets our needs
- it is still very usable even without a nice look and feel
- it has no additional cost
- it does not create unwanted complexity (e.g. having to manage deployment scripts)

## Consequences

A GitHub repository is created at <https://github.com/nicomadev/test-adr>

A more advanced tool may be needed in a mid-term or long-term future if the number of ADRs grows very large.

## More information

N/A
