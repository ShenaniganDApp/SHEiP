---
SHEiP: SHEiP 2 
title: Join POOLHaus
author:  Victor Ginelli (@youngkidwarrior )
discussions-to: https://github.com/ShenaniganDApp/SHEiP/issues/7 
status: Last Call 
category: Informational
type: Operations
created: 2021-07-30
edited: 2021-08-03
requires: N/A
replaces: N/A
---

<!--PROPOSE A NEW SHEiP-->

<!--NOTE: 
You can leave these HTML comments in your SHEiP and delete the visible text guides, they will not appear and may be helpful to refer to if you edit your SHEiP again.-->

<!-- STEPS TO SUBMIT A SHEiP:
1. Complete the header above.
2. Fill in as much content as is appropriate for the status of your SHEiP.
3. Add Github labels for status, category, and type.-->

<!--ADDITIONAL INSTRUCTIONS FOR HEADER SECTION ABOVE-->

<!--<REMOVE>: Remove the <REMOVE> elements from above and below the header. Leave the --- characters.-->

<!--[SHEiP]: Leave this section blank for new issues. Once you submit a PR later in the process, an editor will assign you a canonical number.-->

<!--[title]: Give your issue a concise, descriptive title prefixed by either its *type* for standards SHEiPs or its category for other SHEiPs. (i.e. Development: Smart Contract Upgrade, Meta: Define SHEiP Process, etc.).-->

<!--[status]: Here is a description of status terms.
- `Idea`: a SHEiP issue that is incomplete.
- `Draft`: a SHEiP issue that is complete but undergoing rapid iteration and changes.
- `Last Call`: a SHEiP issue that is stable and ready for final review by the community.
- `Pending`: a SHEiP that has been submitted as a PR or merged but not finalized.-->

<!--[category]: Here is a description of category terms.
- `Standards`: a SHEiP that affects the product or community.
- `Meta`: a SHEiP that affects the governance process for SHEiPs.
- `Informational`: a SHEiP that is merely for informational purposes but requires no action by the community, and will not be merged as a SHEiP.-->

<!--[type]: Here is a description of type terms. These are only applicable to SHEiPs in the *Standards* category.
- `Development`: a SHEiP that affects code or codebase standards.
- `Design`: a SHEiP that affects the way SHE interacts with its members.
- `Operations`: a SHEiP that affects DAO processes or conventions .
- `Documentation`: a SHEiP that affects the written word of SHE-->

<!--[requires]: A list of SHEiP(s) that this SHEiP depends on. *Optional.-->

<!--[replaces]: A list of SHEiP(s) that this SHEiP replaces. *Optional.-->

## Simple Summary
<!--Provide a simplified and layman-accessible explanation of the SHEiP.-->
Join [PoolHAUS](https://medium.com/daohaus-club/poolhaus-and-decentralised-liquidity-provision-ced87ffe656) , a DAO organized by our DAO provider [DAOHaus](http://daohaus.gg) 


## Abstract
<!--A short (~200 word) description of the technical issue being addressed.-->
PoolHAUS is a DAO made to encourage liquidity within the DaoHaus/UberHaus community on HAUS token. In return for locking LP tokens in the DAO for 3 months, DAO members will receive HAUS rewards based on the magnitude of their stake. PoolHAUS will be opening its doors to the public until August 7th. Minimum contribution is 10 HAUS/WETH LP Tokens *or* 1.5 xDai WETH.

## Motivation
<!--Motivation is critical for SHEiPs that want to change SHE. It should clearly explain why SHE is inadequate in its current state and then address the problem that the SHEiP solves. SHEiP submissions without sufficient motivation may be rejected outright.-->
Since we are staying on xDai for the foreseeable future, supporting the xDai community should be part of
 SHE's backbone. With our upcoming application to UberHaus, we can show further support for our DAO platform by pledging some of the treasury to the HAUS token At the same time, we will be receiving HAUS in return for our support, which is a win-win if we are bullish on the state of HAUS token. 

Here are the reward allocation from the article:

> - Over the 3 month period, 2500 HAUS will be issued to PoolHAUS, these rewards will be distributed proportionally based on contributions. These rewards can also be increased by UberHaus if decided by the DAO.
> - WETH contributors to PoolHAUS are given higher rewards than LP contributors; an additional 825 HAUS will be distributed pro-rata.
> - These additional rewards will be airdropped to WETH contributors at the end of PoolHAUS.


## Rationale
<!--The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is works in other environments. The rationale may also provide evidence of consensus within the community, and should discuss important objections or concerns raised during discussion.-->
This is the first Iteration of PoolHaus. Participating could lead to more collaborations between HAUS and PRTCLE in the future. DAOHaus has built a great platform and given an opportunity to mutually benefit between our DAO



## Implementation
<!--The implementations must be completed before any SHEiP is given status "Final", but it need not be completed before the SHEiP is accepted.-->
Here are the requirements from the article:

> - Contributors will pledge a minimum of 10 WETH/HAUS LP tokens from Swapr, or 1.5 WETH to the DAO. Every 100 DAO shares (Loot or Gov) will represent 1 WETH/HAUS LP token or 0.15 ETH.
> - Contributions will be open for a one week window; During which LP tokens & ETH contributions will be pegged at the start of the PoolHAUS contribution window.
> - PoolHAUS will hold its LP position in the minion for 3 months, meaning contributors won’t be able to Ragequit (claim) their LP tokens back from the DAO before this 3 month period ends (Unless otherwise voted by the DAO).

It seems as though a community member @yalormewn is willing to donate their HAUS tokens to this cause, with promise of returned reward at the end of the 3 months. The max Shenanigan can afford to match with is 25,000 DAI, or ~1565.92 HAUS (at time of writing). This opens up more options for SHE

There are a few monetary options. It makes sense to pledge LP Tokens since an extra 825 HAUS will be given to LP pledgers over WETH pledgers
1. Pledge the minimum 10 LP Tokens (no community)
2. Pledge $10,000 worth of LP Tokens (no community)
3. Match $15,000 with community HAUS
4. Match $25,000 with community HAUS

Option 0 - No pledge
Option 1 - will provide very little reward at the minimum but it is very safe
Option 2 - gives decent rewards and allows SHE to keep everything that is earned,
Option 3 - is more in our budget than Option 4, but gives us 3x the rewards as Option 2. We would have to give donators back their share of the rewards (e.g. 1/2)
Option 4 - Same as 3, but gives us 5x rewards as Option 2


We will use a gnosis multisig on xdai controlled by SHE Core to pledge the DAO, since a DAO vote will take too long to make the 1 week pledge window. We will have use blockscout to make sure Yalor gets his fair share of rewards back at the end of the 3 months.

## Security Considerations
<!--All SHEiPs must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. SHEiP submissions missing the "Security Considerations" section will be rejected. An SHEiP cannot proceed to status "Final" without a Security Considerations discussion deemed sufficient by the reviewers.-->
Using a Gnosis safe should make the shares secure.

If we are not feeling bullish on HAUS/xDai, then this would not be smart. We should probably consider a migration to another chain if we don't feel this is a good move. We are wasting time on xDai if we are not open to collaborating with other xDai projects.


## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
