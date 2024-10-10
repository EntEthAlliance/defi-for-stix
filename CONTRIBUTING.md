# Contributing to the DeFi STIX extensions

Comments should be made by adding a comment to an [open issue](https://github.com/EntEthAlliance/EthTrust-public/issues) if there is a relevant issue already, or by creating a
[new issue](https://github.com/EntEthAlliance/EthTrust-public/issues/new/choose).

If proposals are editorial in nature (i.e. they clarify wording, fix spelling mistakes or obvious logic errors),
the process is fairly straightforward.

If a proposal suggests a substantive change - e.g. adding a new requirement, or changing a requirement so it will be tested differently,
through the issue template we request the commenter to complete the
[EEA Non-member participation agreement](https://github.com/EntEthAlliance/EthTrust-public/blob/main/EEA-Non-Member-Participation-Agreement.pdf).
Essentially this is an agreement not to introduce material covered by a "submarine patent".

## How we (PROPOSE TO) work

Note that this repo and workstream is in setup, and we can adjust these things as needed.

### Meetings

We expect to hold a teleconference by zoom every week on a day before Thursday.

The meeting agenda will be sent at least 48 hours earlier based on the relevant [milestone](https://github.com/EntEthAlliance/eta-registry/milestones).
Items on the agenda will generally have one [Agenda Label](#agenda-labels) giving a sense of what stage the proposal is,
and can have other informative labels.

### Github - specs and code

The basis of our work is through this Github repository.

The following information summarises how we manage proposals and meeting agendas:

#### Issues

The core tool for work is issues.

An issue is the way to propose a change to the specification
or to note that something should be fixed, or to the registry code,
or for an administrative question such as suggesting we change meeting times.

While we prefer that issues proposing changes to the spec are accompanied
by a Pull Request implementing the change, it is OK just to comment directly in the issue;
the editor(s) can turn that into a Pull Request.

Meeting agenda are driven by issues. It is valuable to turn up to a meeting
to discuss an issue, but we recognise that people cannot make every meeting.
It is a reasonable alternative to make comments on an issue - during a meeting
we will check for comments on each issue under discussion.

If you are planning to work on a particular issue, e.g. developing a Pull Request
to resolve it, please assign yourself to the issue so others know and don't repeat the work.

#### Pull Requests

(Often called a "PR")

The "preferred" way to resolve an issue is with a Pull Request - a proposed change
that we can comment on, adjust, and decide on before putting it into the "main" branch
of our work.

If you are a recognised contributor, you will have permission to branch the repo.
If not, please feel free to fork it to propose your first PRs, until we add you to the contributor team.

For Pull Requests other than simple editorial clarification, please raise an issue,
so people can browse the closed issues list in the future and discover that we discussed
something.

#### Milestones

Meeting agenda are based on GitHub milestones,
to make sure the group has visibility into the development of agenda and timing of discussions.
All members in principe have the ability to assign a label and milestone to any issue or PR.

If you would like to add an item for a particular meeting, please feel free to do assign it
to the milestone before the deadline,
with appropriate labels (most specifically including one of ["Please dpDiscuss"](#please-discuss),
["individual resolution"](#individual-resolution) or ["Bulk Resolution"](#bulk-resolution)).

#### Agenda Labels

There are four labels that are used to sort Agenda Items:

##### Please Discuss
This is for proposals or PRs that are not ready to be resolved, but for which you would like input.
No Final decision will be taken about these on a meeting - the likey outcome is that we either
continue to discuss, or recommend a solution that might be presented as soon as the next meeting
for [Individual Resolution](#individual-resolution) or Bulk Resolution](#buk-resolution).

##### Individual Resolution
This is for proposals that we expect to resolve, with some discussion and perhaps some changes,
or choosing between options that are presented in the issue.

##### Bulk Resolution
This is for proposals that we believe have consensus and will simply be accepted,
perhaps with trivial changes to be applied by the editors (including managing merge conflicts).
This will happen even if a meeting doesn't make other decisions due to a lack of quorum.
If there is an objection in the issue/PR before the meeting, or at the meeting, they are likely
to be postponed to another meeting rather than discussed at length.

##### Minutes
If you want to propose a change to meeting minutes, please do it as an issue or PR with the label "minutes".
Minutes are assumed to have been accepted by the next meeting if there are no such change proposals,
but it is acceptable to make a later proposal that the group will discuss.
