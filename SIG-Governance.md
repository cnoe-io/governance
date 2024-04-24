# SIG Governance

CNOE Special Interest Groups (SIGs) generally align with the scope, purpose, and and governance processes defined by [Kubernetes SIG Governance](https://github.com/kubernetes/community/blob/master/committee-steering/governance/sig-governance.md). Although there are many cases where we cannot replicate the specifics of this Kubernetes process, we aim to align ourselves with the spirit of this process.

## Requirements for a SIG

- Have an approved Charter under sigs/sig-name/charter.md.
- Meet regularly, at least for 30 minutes every 3 weeks, except November and
  December.
- Keep up-to-date meeting notes, linked from the SIG's page in the community
  repo..
- Ensure related work happens in a project-owned GitHub org and repository,
  with code and tests explicitly owned and supported by the SIG, including
  issue triage, PR reviews, test-failure response, bug fixes, etc.
- Use the community slack as the primary means of working, communicating,
  and collaborating, as opposed to private emails and meetings.
- Ensure contributing instructions (CONTRIBUTING.md) are defined in the SIGs
  folder located in the community repo.

## Roles

As we are a smaller community than Kubernetes, we have simplified the Roles for SIG and their subprojects. We also are folding in [community roles](https://github.com/kubernetes/community/blob/master/community-membership.md) to SIGs and their subprojects.


| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| Reviewer | Review contributions from other members | History of review and authorship in a subproject | [OWNERS] file *reviewer* entry |
| Approver | Contributions acceptance approval| Highly experienced active reviewer and contributor to a subproject | [OWNERS] file *approver* entry|
| Subproject owner | Set direction and priorities for a subproject | Demonstrated responsibility and excellent technical judgement for the subproject | [OWNERS] file *owners* entry |
| Lead | Set direction and priorities for a SIG | Demonstrated responsibility and excellent technical judgement for the SIG | sigs/sig-name/OWNERS file *owners* entry |