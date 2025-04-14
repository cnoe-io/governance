# SIGs

Special Interest Groups (SIGs) are persistent open groups that focus on a part of the project. SIGs must have open and transparent proceedings. Anyone is welcome to participate and contribute provided they follow the [Code of Conduct](CODE-OF-CONDUCT.md).

Approval of a SIG charter (and therefore creation of a SIG) is made by the CNOE Steering committee following their standard decision making processes.

# Requirements

SIGs must have at least one and ideally two SIG chairs at any given time. SIG chairs are intended to be organizers and facilitators, responsible for the operation of the SIG and for communication and coordination with the other SIGs, the Steering Committee, and the broader community.

Each SIG must have a charter that specifies its scope (topics, subsystems, code repos and directories), responsibilities, areas of authority, how members and roles of authority/leadership are selected/granted, how decisions are made, and how conflicts are resolved.

A primary reason that SIGs exist is as forums for collaboration. Much work in a SIG should stay local within that SIG. However, SIGs must communicate in the open, ensure other SIGs and community members can find notes of meetings, discussions, designs, and decisions, and periodically communicate a high-level summary of the SIG's work to the community.

## Process Requirements

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

# Subprojects

Specific work efforts within SIGs are divided into subprojects. Every part of the CNOE code and documentation must be owned by some subproject. Some SIGs may have a single subproject, but many SIGs have multiple significant subprojects with distinct (though sometimes overlapping) sets of contributors and owners, who act as subproject’s technical leaders.

# Standard Roles

As we are a smaller community than Kubernetes, we have simplified the Roles for SIGs and their subprojects. SIGs may choose to have alternate roles defined in their charter, but otherwise the following roles should be used within the SIG.


| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| Reviewer | Review contributions from other members | History of review and authorship in a subproject | [OWNERS] file *reviewer* entry |
| Approver | Contributions acceptance approval| Highly experienced active reviewer and contributor to a subproject | [OWNERS] file *approver* entry|
| Subproject owner | Set direction and priorities for a subproject | Demonstrated responsibility and excellent technical judgement for the subproject | [OWNERS] file *owners* entry |
| Lead | Set direction and priorities for a SIG | Demonstrated responsibility and excellent technical judgement for the SIG | sigs/sig-name/OWNERS file *owners* entry |


> Note: The content in this page is largely based on the [Kubernetes Community Documentation](https://github.com/kubernetes/community/blob/master/README.md) and the [community roles](https://github.com/kubernetes/community/blob/master/community-membership.md) documentation.