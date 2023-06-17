# Create a third-party packages use policy

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

The use of third-party packages (specifically NuGet packages) can cause some issues if they are not safe (malicious code), not properly maintained (unreliable or outdated code) or use incompatible licenses (legal issues).

## Decision

Use and enforce a strict policy on the use of third-party packages adressing the following concerns:

- Safety
- Reliability
- Licensing

## Consequences

The policy is created at <https://link-to-the-policy> and shared to the team.

## More information

The policy can evolve without needing a new ADR.

Further reading:

- [Attackers are starting to target .NET developers with malicious-code NuGet packages](https://jfrog.com/blog/attackers-are-starting-to-target-net-developers-with-malicious-code-nuget-packages/)
- [How to Avoid Costly Lawsuits from Unexpected NuGet License Agreements](https://blog.inedo.com/nuget/how-to-avoid-costly-lawsuits-from-unexpected-nuget-license-agreements/)
- [How to Create a Package Approval Workflow for NuGet](https://blog.inedo.com/nuget/package-approval-workflow/)
