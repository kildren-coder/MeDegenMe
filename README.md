# MeDegenMe

## Overview
MeDegenMe is a platform that combines DEGEN staking with fair distribution of MEME tokens, ensuring user security in MEME projects through Web3 technologies.

---
## Interactive Roles
### USER
- Users stake DEGEN to receive 1:1 voting points, updated weekly, with unused points cleared weekly.
- Users vote on MEME project details like tokenomics, project revenue, airdrops, total supply, and tax allocation using points on frame or website.

### MEME Project Owners
- Register MEME projects on MeDegenMe for an exclusive API for frame authenticity and contract upgrades.
- Delegate proxy and logic contract ownership to MeDegenMe for deployment and upgrades.
- MeDegenMe executes contracts based on community votes, ensuring project continuity and preventing exit scams.

---
## Workflow Example
### MEME Project Owners:
1. Register a new MEME project on MeDegenMe(only with name and symbol), receive an API for authenticity.
2. Syndicate generates template Proxy contract based on project details, transferring ownership to MeDegenMe.
3. The project owners set up voting proposals for the project on MeDegenMe, and the content is written into the smart contract for user reference.
4. The project owners deploy the contracts to be upgraded (such as introducing maximum supply, presale whitelist, etc.) and upgrade the logic contract (i.e., how the contract will be upgraded based on the voting).
5. The project owners make the code of the above contracts public and transfer ownership to MeDegenMe for user inspection.
6. The project owners can create a vote frame on Warpcast (requiring an API to prevent forgery by other users) or guide users to vote on the MeDegenMe website.
7. Based on the voting results, MeDegenMe is responsible for contract upgrades and execution.
8. The project owners can use the Points staked by users as a measure of participation level and reward early participants with airdrops or presale whitelist based on these Points.

### User:
1. Stake DEGEN on Degen Chain to receive vote points.
2. Users can use vote points on Warpcast to vote for their favorite MEME projects. With the anti-counterfeiting API in place, users can trust that the vote frames they participate in are created by the MEME project owners and are not fraudulent attempts to deceive users for points.
3. Before voting, users can visit the official MeDegenMe website to check detailed information about MEME projects, especially to verify if upcoming upgrade contracts have any vulnerabilities.

---
## Core Goals
To maximize the security of user participation in MEME projects.

Users should only invest real money in MEME projects after ensuring the security and rationality of the contracts. Before that, they participate using the vote points they obtained for free, minimizing potential monetary losses for users.

Since users inspect each upgrade of the MEME contract and ownership and execution rights are with MeDegenMe, even if the MEME project owners decide to exit, MeDegenMe can assist community users in continuing the MEME project.

I hope this project will help Degen Chain and Warpcast become the most reliable MEME community, making people realize that to participate safely in MEME, they should turn to Degen Chain and Warpcast.

---
## Future Development
Plans: As an independent developer with limited programming skills and Web3 experience, I am seeking help with development. I will focus first on contract writing and off-chain server development, while frontend and frame development will be postponed.

Many contracts and vote frames in the process can be modularly deployed, and assistance from syndicates would be greatly appreciated.

Some ideas:
1. More design considerations, especially regarding security: issues like the excessive power of MeDegenMe, MEME project owners manipulating proposals to their advantage under extreme conditions, and fraudulent framing for points.
2. Users can exchange DEGEN for Super points, which are not time-limited. Users can quickly accumulate a large number of points, encouraging project owners to give these points greater weight and rewards.
3. Distinguishing between vote frames and points for voting on the official website, such as offering higher returns on points from vote frame channels, to encourage more users to participate in the Warpcast ecosystem.
