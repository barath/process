This repository details how changes to Solid may be proposed and accepted.

# Solid Specification
The following describes how changes to the specifications in the Solid ecosystem may be proposed and accepted.

Development in the Solid ecosystem occurs in the [Solid Specifications](https://github.com/solid/specification) repository. The [Unofficial Draft](https://github.com/solid/solid-spec) predating current development is still available for historical reference.

Anyone may participate in this process. Please read the [Code of Conduct](code-of-conduct.md) before doing so.

## Contributors

Any individual who has been involved in proposals to improve the [Solid Specification](https://github.com/solid/specification) has provided a valuable service to the [Solid Project](https://www.solidproject.org) and is encouraged to continue.

Many types of contributions are welcome, including identifying problems, asking questions, and proposing normative changes.

There are many topics, problems, or ideas best addressed by a group of people with specific domain expertise in [Solid Panels](#solid-panels).

### Solid Panels

Solid Panels are groups of individuals focused on a specific problem or domain relevant to Solid, with an aim to propose changes to the [Solid Specification](https://github.com/solid/specification). Domains may be technical, non-technical, or some combination of the two. For example, a Security Panel could focus on the evaluation and advancement of the Solid security model. Only those who have agreed to the [W3C Community Contributor License Agreement](https://www.w3.org/community/about/agreements/cla/) may participate in a Solid Panel.

New panels may be proposed by submitting an issue to the [solid/process](https://github.com/solid/process) repository. Establishing a new panel requires the endorsement of at least one member of the [Editorial Team](https://github.com/orgs/solid/teams/editors). To receive endorsement, the proposed panel submission must include:

1. A stated purpose
1. One or more initiatives that will be actively pursued and tracked in regular panel sessions to advance the stated purpose
1. Demonstrable support of at least five prospective participants

The panel proposal can be revised until at least one member of the Editorial Team endorses the proposal. Submissions that fail to receive endorsement may be removed by Solid Administrators after six months.

Any Editor endorsing a panel is expected to attend the panel regularly, and to provide the panel insight on specification priorities and support the work of the panel.

Each panel is chaired by one or more Panel Chairs. An Editorial Team member endorsing a panel is responsible for appointing the Panel Chairs, barring any objections from another Editor, another Panel Chair of the same panel, or objection from a majority of panel members. The Solid Director reserves the right to appoint and/or change Panel Chairs. In the event that an Editor is nominated as a Panel Chair, they must be appointed by another member of the Editorial Team.

 Responsibilities of a Panel Chair include but are not limited to:

- Coordinating and communicating panel initiatives
- Working with Editors on prioritizing panel initiatives
- Ensuring panel meetings are focused on advancing panel initiatives
- Ensuring every panel meeting has a clear goal and agenda
- Ensuring all actions arising from meetings are tracked to completion
- Ensuring target dates are set for objectives
- Ensuring panel decisions, activities, and achievements are tracked and communicated

Specification changes proposed by a panel are subject to the [proposal review process](#reviewing-proposals).

Those interested in participating in a panel can find a list of active panels at [panels.md](panels.md).

Panels may request to have a repository created within the [Solid Github Organization](https://github.com/solid) by creating an issue in [solid/process](https://github.com/solid/process). The request should include the proposed name of the repository and how it will be used. Any editor may reject a proposed name and request an alternative. ==All panel members will receive [_Maintain Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on the panel repository, unless it is subject to editorial review, which would require that it employ a [different permission structure](#repositories).== Panel repositories that are inactive for more than six months may be archived by Solid Administrators.

Panels may request to have a gitter channel created within the [Solid Gitter Organization](https://gitter.im/solid) by creating an issue in [solid/process](https://github.com/solid/process).

## Stakeholders

Stakeholders are those affected by normative changes to the [Solid Specification](https://github.com/solid/specification). There are two types of Stakeholders: [Solid Users](#solid-users) and [Solid Implementers](#solid-implementers). It is important to consider them both when proposing changes, and adhering to the W3C [priority of constituencies](https://www.w3.org/TR/html-design-principles/#priority-of-constituencies) is encouraged. A Stakeholder may be both a user and an implementer.

Stakeholders who have opted to identify themselves publicly are listed at [stakeholders.md](stakeholders.md). Anyone may decide to identify themselves publicly as a Solid Stakeholder, but it is not mandatory. Identified stakeholders may be consulted for feedback as part of the editorial process.

### Implementers
Solid Implementers are organizations who are implementing the [Solid Specification](https://github.com/solid/specification). A Solid Implementer may be any combination of Identity Provider, Pod Provider, and Application Provider.

## How to Make Changes

This section details how changes to the [Solid Specification](https://github.com/solid/specification) may be drafted, proposed, and accepted.

Anyone may submit a proposal to alter this process. These proposals will not be reviewed by the editors. They will be reviewed only by [Tim Berners-Lee](https://github.com/timbl), who is the Solid Director.

### Drafting proposals

Anyone may propose improvements to the [Solid Specification](https://github.com/solid/specification). Here are some examples of different ways to contribute:

- Submit a pull request or issue on the [Solid Specification repository](https://github.com/solid/specification) in GitHub
- Make a suggestion to the Solid Authorization Panel chat room about a change you'd like to see in Web Access Control
- Make a suggestion on the Solid W3C Community Group mailing list to form a new Solid Panel, or join an existing Solid Panel
- Propose an item for the W3C Solid Community Group call

Proposals for substantive changes to the [Solid Specification](https://github.com/solid/specification) go through an editorial review process. A change is considered substantive when it alters the normative text of the Solid Specification or the Solid Roadmap. Any proposal must be realistic and reasonable to implement, preferably with example implementations, and demonstrable support from Implementers.

Any proposal should also be accompanied with a reasonable explanation of the need for the proposed change. For example:

- Adding a new capability that satisfies one or more new use cases, or to reflect a new capability already incorporated consistently into multiple implementations.
- Removing something because it was never adopted by Implementers for legitimate reasons, or because there has been a collective shift in focus away from that feature and it no longer makes sense to keep it.
- Changing something to a simpler design that is able to address the same use case(s) with less complexity, or a change that resolves one or more identified issues in real-world use.

A draft proposal often involves public discussion before being formally presented for review. After these discussions have occurred and a draft proposal has reached a sufficient level of maturity, it should be presented as a candidate proposal, asking Stakeholders and Panels if there are any major objections.

The [Solid Editors](https://github.com/orgs/solid/teams/editors) [maintain a monthly development cycle](solid-editors-tr-process.md) in which they select issues from the open issues for consideration in the next time period to help focus the community towards efficiently resolving outstanding issues. It is hoped that community members will participate in the process, guided by the Solid Editors and within the time frames they set.

When there are objections, notify the Solid Panels and Stakeholders about the final proposal with an invitation to vote. If there are options, detail them along with the implications of the options. The final proposal needs to be open for one week to give others a chance to vote. To show your support for a proposal write +1. To show your disapproval for a proposal write -1 along with a detailed reason for the disapproval and a suggestion for a preferred alternative. To abstain type 0 when you have no opinion. If you do not vote by the end of the week it will be assumed that you abstain. At the end of the week anyone may publish an overview of the vote results per Solid Panel and Stakeholder.

### Reviewing proposals

Candidate proposals to the [Solid Specification](https://github.com/solid/specification) submitted for review go through an editorial process before they are accepted.
Candidate Proposals to change the Solid Specification must be submitted for editorial review before they are accepted, along with the results of any votes taken.

To help broad consensus form, it is suggested that each proposal be brought to the attention of the Editors at some defined contact points during its life cycle. These contact points are:
1. When a reason to change or extend the specification is first encountered, an [issue is opened](https://github.com/solid/specification/issues/new). The issue is then used for further communication with the Editors.
1. Panels may create or adopt issues, and Panels should notify Editors that such discussion has started.
1. When a Panel reaches rough consensus on an issue, the Panel should notify the Editors, indicating in informal text what the consensus entails and who participated in forming it.
1. When a Panel starts drafting the text of a proposal, the Panel should notify the Editors.

The above is not required and may be superfluous for small changes, but it is likely to speed up the overall process for larger issues.

An Editor determines whether a Candidate Proposal includes a substantive change and marks it accordingly. If there is any disagreement among Editors, the Candidate Proposal will be automatically marked as including a substantive change.

Candidate Proposals with substantive changes require three Editors who are assigned to the material being modified to actively approve the proposal, with no Editors from the Editorial Team actively rejecting. If there are less than three Editors assigned to the material being modified, then other Editors from the Editorial Team may participate.  Editors may abstain. Candidate Proposals with substantive changes must remain open for at least one week before final acceptance. If an Editor does not vote by the end of that week it will be assumed that they abstained, providing a good faith attempt has been made to involve those who may be likely to disagree. Once the Candidate Proposal has successfully passed editorial review and the specified wait-time has elapsed, it may be merged by an assigned Editor.

Candidate Proposals without substantive changes require one Editor assigned to the material being modified to actively approve the proposal, with no Editors from the Editorial Team actively rejecting, and may be merged immediately by an assigned Editor. An assigned Editor may approve and merge their own non-substantive changes. Anyone from the Editorial Team has the right to revert a non-substantive change, but are encouraged to communicate with the assigned Editor that merged it first. Any revert must be accompanied by a reasonable explanation. If the change is reverted because they believe it to be substantive, that must be included in the explanation.

### Vocabulary Management

The [W3C Solid Community Group](https://www.w3.org/community/solid/) handles the management of Solid vocabularies under its responsibility through the [solid/vocab](https://github.com/solid/vocab) repository.

The policy for the management of Solid vocabularies under the W3C namespace is described in [Adding to W3C RDF Namespaces](https://www.w3.org/2016/08/namespaces/).

## Editorial Structure

Editor appointments and their respective assignments are made by the Solid Director. The Editorial Team is comprised of all the Editors appointed by the Solid Director, who are listed at [editors.md](editors.md), along with their assignments, contact details, and affiliations. Anyone may apply to be an Editor, and must include one or more requested editorial assignments as part of their application. These requests are not reviewed by other Editors. They are reviewed only by the Solid Director. Editor applications that can demonstrate the support of a relevant panel or group of community members will be favorably considered.

Editors belong to the [Editorial Team](https://github.com/orgs/solid/teams/editors) in the [Solid GitHub Organization](https://github.com/solid).

### Repositories

Repositories requiring editorial review are listed in [editors.md](editors.md#editorial-assignments). Each repository has one or more assigned editors, and only assigned editors are permitted to merge into the master branch of these repositories, per the [proposal review process](#reviewing-proposals).

Editors have [_Admin Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on the repositories they are assigned to, and are permitted to grant [_Write Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) to other contributing authors on the same. All members of the Editorial Team have [_Write Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on all repositories requiring editorial review listed in [editors.md](editors.md).

# Test Suite
Test Suite Developers work with the aim is to develop a [test suite](https://github.com/solid/test-suite) that can be used to verify an implementation against the Solid specification.

# Administration

Administrators are granted privileged access to control the tools, systems, and services used for advancing the Solid. This includes the [Solid GitHub](https://github.com/solid) organization, [Solid Gitter](https://gitter.im/solid/home) channels, the [Solid Forum](https://forum.solidproject.org), and the [Solid Website](https://www.solidproject.org).

Administrators belong to the [Administrators Team](https://github.com/orgs/solid/teams/administrators) in the [Solid GitHub Organization](https://github.com/solid) and have [_Admin Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on all repositories therein. Administrators have [_Owner Permissions_](https://help.github.com/en/articles/permission-levels-for-an-organization#permission-levels-for-an-organization) for the [Solid GitHub Organization](https://github.com/solid).

### Becoming an Administrator

Administrators are appointed by the Solid Director. Administrators are listed at [administrators.md](administrators.md) along with their contact details and affiliations. Anyone may apply to be an Administrator. Administrator applications are not reviewed by other Administrators. They are reviewed only by the Solid Director.

# Solidproject.org Website

[Creators](https://github.com/solid/process/blob/master/creators.md) independently assist with keeping [solidproject.org](https://solidproject.org/) up to date.

Anyone can make suggestions by creating issues or submitting pull requests
to the [solid/solidproject.org](https://github.com/solid/solidproject.org) repository.

Minor changes (such as spelling, grammar, and broken links) do not require review.
Larger chunks of texts should be reviewed by a Creator or Editor for technical correctness.
Changes to the main messaging require an approving review by the Director.

# Solidcommunity.net

[Solidcommunity.net](https://solidcommunity.net) is a free pod hosting service
maintained by the Solid Project for research, development, and experimental,
non-commercial use of Solid by community members.

It is administered by [System Operators](system-operators.md), with additional
support from Solid Project [Administrators](administrators). System Operators
are appointed by the Solid Director.

