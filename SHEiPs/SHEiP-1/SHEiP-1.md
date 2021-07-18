---
SHEiP: SHEiP-1
title: Shenanigan Improvement Proposals (SHEiP)
author: Victor Ginelli (http://github.com/youngkidwarrior)
discussions-to: https://github.com/Shenanigannetwork/SHEiP/issues/1
status: Draft
category: Meta
type:
created: 2021-07-15
requires:
replaces:
---
  
## Simple Summary

This proposal describes the process for SHE Improvement Proposals (SHEiPs).


## Abstract

SHE Improvement Proposals (SHEiPs) are standards for improving the Shenanigan platform, including core development updates, community organization, design standards, DAO operations, and written documentation. As a result, SHEiPs empower SHE to mature as an open source project and community.


## Motivation

Here are some of the reasons why Shenanigan needs a SHEiP process:
- To define an explicit proposal process for Shenanigan improvements
- To make it easy for community members to contribute to the development of the DAO
- To encourage well thought out, high value discussion about growing SHE
- To provide a way to discover implementation standards accepted by the community
- To provide a vehicle for community discussion around important topics

## Specification

### Process

#### 1. Propose a new idea

> Ideas are incomplete proposals meant to initiate community conversation.

Create a new issue in the SHEiP repository containing the idea for your your proposal, following the [SHEiP template](https://github.com/ShenaniganDApp/SHEiP/issues/new?assignees=&labels=&template=new-SHEiP.md&title=) format. Be sure to add the **Status: IDEA** label to your issue.

#### 2. Complete your draft

> Drafts are complete proposals, but still undergoing rapid iteration and change.

Complete your proposal by filling out all appropriate fields in the SHEiP template. Update your proposal to **Status: DRAFT** in the issue header and Github label. Gather community feedback and make improvements as required.

#### 3. Enter last call for community feedback

> Last Calls are stable proposals ready for final review by the community.

Once you feel that your proposal is stable and ready for final review by the community, update your proposal to **Status: LAST CALL** in the issue header and Github label. In order to proceed beyond Last Call, your issue must remain in Last Call for at least 2 weeks and any technical changes that are requested must be addressed by the author.

#### 4. Submit a Pull Request

> Pull Requests are SHEiPs ready for consideration by editors and/or core developers.

When your proposal exits Last Call, you should submit a Pull Request to the SHEiP repository. To do this, fork the SHEiP repository by clicking "Fork" in the top right. Add your SHEiP to your fork of the repository. Update your proposal to **Status: PENDING** in the issue header and Github label (on both your previous open issue and new PR). Then, submit a Pull Request to the SHEiP repository.

Upon submission an editor will manually review the first PR for a new SHEiP, assign it a canonical number (i.e. SHEiP-1), and merge it into the SHEiP repo. They will then reach out to discuss next steps to achieve finalization. These steps will depend on whether or not your SHEiP is of type Core.

*When submitting your Pull Request:*

- Images: If your SHEiP requires images, the image files should be included in a subdirectory of your SHEiP folder as follows: `SHEiP-N/assets` (where **N** is to be replaced with the SHEiP number). When linking to an image in the SHEiP, use relative links such as `./assets/image.png`.

- Tables: If your SHEiP requires csv tables, the table csv files should be included in a subdirectory of your SHEiP folder as follows: `SHEiP-N/tables` (where **N** is to be replaced with the SHEiP number). When linking to a table in the SHEiP, use relative links such as `./tables/table.csv`.

#### 5. Get your SHEiP finalized

> Finalized SHEiPs are SHEiPs that are have been approved.

##### 5a. If your SHEiP is an Improvement SHEiP

An editor will reach out to provide the dates of the upcoming Shenanigan Weekly Huddles. Once you select one, your issue will be added to the agenda for that huddle where it will be discussed to take it to a community vote. 

After the huddle, a team member will create a new [snapshot vote](https://snapshot.org/#/shedapp.eth) with the aforementioned SHEiP. The vote will last 3-5 days and will signal the community to vote on the preferred outcome.

Once the vote is finalized, SHEiP editors will update your SHEiP to **Status: ACCEPTED**. Once your proposal has been implemented into the SHE product, SHEiP editors will update your SHEiP to **Status: FINAL**.

##### 5b. If your SHEiP is a non-Improvement SHEiP

An editor will ask if anyone objects to it being finalized. If not, the SHEiP will go to [snapshot](https://snapshot.org/#/shedapp.eth) and if the community does not vote for it to pass - for instance, because contributors point out significant issues with the SHEiP - they may close the PR and request that you fix the issues in the draft before trying again. If the editor finds there is rough consensus, they will merge the PR and update it to **Status: FINAL**.

### SHEiP Terms

#### Categories

- `Improvement`: a SHEiP that affects the product or community.
- `Meta`: a SHEiP that affects the governance process for SHEiPs.
- `Informational`: a SHEiP that is merely for informational purposes but requires no action by the community, and will not be merged as a SHEiP.

#### Types

> Only applicable to SHEiPs of type *Standards*.

- `Development`: a SHEiP that affects code or codebase improvements.
- `Design`: a SHEiP that affects the way SHE interacts with its members.
- `Operations`: a SHEiP that affects DAO processes or conventions .
- `Documentation`: a SHEiP that affects the written word of SHE

#### Statuses

- `Idea`: an SHEiP issue that is incomplete.
- `Draft`: an SHEiP issue that is undergoing rapid iteration and changes.
- `Last Call`: an SHEiP issue that is stable and ready for final review by the community.
- `Pending`: an SHEiP that has been merged but not finalized.
- `Accepted (Core)`: an SHEiP of type Core that has been accepted by the core devs to be included in a future network upgrade.
- `Final (Core)`: an SHEiP of type Core that has already been released in a network upgrade.
- `Final (non-Core)`: a non-core SHEiP that has met all criteria and is finished.


## Rationale

It is prudent to look at other successful examples of open source software governance. SHEiPs are inspired by the previous work of Ceramic Network(CIPs), Ethereum (EIPs) Bitcoin (BIPs), Python (PIPs), and others. SHEiP is slightly different in implementation than those examples, but shares many similarities. In some cases, SHEiP even borrows certain language from those examples.


## Implementation

- **Official Process**: This SHEiP and the [README](https://github.com/Shenanigannetwork/SHEiP) of the SHEiP repository.
- **Issue Template**: Create a new SHEiP issue [here](https://github.com/Shenanigannetwork/SHEiP/issues/new?assignees=&labels=&template=new-SHEiP.md&title=).


## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
