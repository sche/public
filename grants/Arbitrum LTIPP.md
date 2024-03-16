# SECTION 1: APPLICANT INFORMATION

**Applicant Name:** Andrey Scherbovich

**Project Name:** Goverland

**Project Description:** Goverland is a mobile app that allows DAO participants to follow updates, vote, and discover insights. With features like push notifications and wallet connectivity, Goverland simplifies voting, making DAO participation more convenient and inclusive. We already support participating in Snapshot off-chain voting. With additional support, we hope to integrate on-chain voting for Arbitrum DAO soon.

**Team Members and Roles:**

- [Andrey Scherbovich](https://www.linkedin.com/in/scherbovich/), CEO
- [Pavel Shapovalov](https://www.linkedin.com/in/shapovalov-pavel/), CTO
- [Varvara Beloveshkina](https://www.linkedin.com/in/varvara-beloveskina-20479313/), BD
- [Sergey Larionov](https://www.linkedin.com/in/s-larionov/) - Backend Engineer
- [Eugenia Shalai](https://www.linkedin.com/in/jennyshalai/) - iOS Engineer
- [Elena Kirina](https://www.linkedin.com/in/elena-kirina-5698481b6/) - Designer

Project Links: 

- [goverland.xyz](https://goverland.xyz/)
- [GitHub](https://github.com/goverland-labs)
- [iOS TestFlight App](https://testflight.apple.com/join/RXPCZXIg)
- [Discord](https://discord.gg/uerWdwtGkQ)
- [X (Twitter)](https://twitter.com/goverland_xyz)

### Contact Information

**Point of Contact:**: @scherbovich

**Point of Contact’s TG handle:** @scherbovich

**Twitter:** AScherbovich

**Email:** andrey@goverland.xyz

Do you acknowledge that your team will be subject to a KYC requirement?: **Yes**

# SECTION 2a: Team and Product Information

## Team Experience

Our team boasts extensive technical expertise, with a proven track record of contributing to Open Source projects and delivering successful endeavors such as Gnosis Safe Mobile.

Our team's vision for Goverland is to democratize governance for DAO participants, fostering increased participation rates and enhancing delegate accountability.

## Product Features:

Our public release will be in April. With the full support of Snapshot protocol voting initially, with the help of this grant, we will add support of Arbitrum DAO on-chain voting on iOS and iPadOS happening on the Arbitrum chain within 12 weeks while the grant program runs.

### Features avaialble during the public laucnh in April:

- **Notifications**: Users can opt-in to receive push notifications for key DAO updates, including:
  - New proposals
  - Proposals quorum achievements
  - Voting reminders as deadlines approach
  - Final voting outcomes

- **DAO Insights**: Our platform will provide valuable analytics, such as:
  - Success rates of proposals
  - Monthly active voters
  - Voting frequency among users
  - Top voters ranked by average voting power

- **Voting Accessibility**: Users can conveniently participate in voting processes using mobile devices, ensuring on-the-go engagement with governance activities.

These features collectively aim to streamline the user experience, promote informed decision-making, and foster a more robust and engaged DAO community.

### Why bring ArbitrumDAO On-Chain Voting Experience to mobile

ArbitrumDAO stands as one of the largest DAOs, boasting approximately [~60K monthly active voting addresses on Snapshot](https://dune.com/queries/3480528/5849863) and [~20K monthly active voting addresses on-chain](https://dune.com/queries/3480520/5849859).

Presently, ArbitrumDAO participants navigate through multiple platforms to engage in full-cycle governance, including the ArbitrumDAO forum, Snapshot for off-chain voting, and Tally interface for on-chain voting. 

Through the Goverland Mobile App, we aim to streamline this process by consolidating vital information into one accessible platform, providing users with a seamless governance experience on mobile devices.

In this grant proposal, we seek support to integrate ArbitrumDAO's on-chain voting experience into the Goverland App.

### Novelty and Innovation

Goverland introduces a groundbreaking mobile experience for voters within the largest Snapshot DAO with on-chain governance, ArbitrumDAO, revolutionizing accessibility and convenience for participants.

### Composability with Other Projects

Our project embraces composability, as many components delivered will be open-sourced, facilitating seamless integration of on-chain governance into Goverland for other DAOs within the Arbitrum ecosystem.

### Retention Measurement

We visualize new and returning DAO users inside the App and voters' participation frequency.

<img src="https://github.com/sche/public/blob/708c0c600cd49c18c5ff10898cd90df6bc5534f6/images/Arbitrum%20Insights%20-%20Mar%2016%2C%202024.png?raw=true" width="400"/>

### Relevant Usage Metrics

To measure the positive outcome this grant results, we will visualize the following usage metrics:
- Percentage of voting power participating in Snapshot/On-chain voting.
- Percentage of token holders participating in Snapshot/On-chain voting.
- Distribution of votes across different interfaces.
- Voter retention rate.
- Identifying the top voters based on average voting power over the last six months.

### Team-Controlled Wallets and Incentives

Not applicable

### Utilization of Third-Party Consultants

No, we did not utilize grants consultants or any other third-party entities in the drafting of this proposal.

## SECTION 2b: PROTOCOL DETAILS

### Is the protocol native to Arbitrum?

ArbtirumDAO on-chain voting using Governor contract modification is native to Arbitrum. We don't own the voting protocol, but we build a convenient mobile app that brings more users and usage to the network.

Our open-source infrastructure is designed to be generic-purpose for all types of DAOs. However, custom integration is required for large DAOs like Arbitrum that utilize a custom implementation of on-chain voting.

### On what other networks is the protocol deployed?

ArbtirumDAO voting is on the Arbitrum network.
The Goverland Mobile App supports off-chain voting using Snapshot only at the moment.

### Do you have a native token?

No, there are no plans for Goverland native token at this time.

### Past Incentivization

No.

### Current Incentivization

No.

### Have you received a grant from the DAO, Foundation, or any Arbitrum ecosystem related program?

No.

### Protocol Performance

[~20K monthly active voting addresses on-chain for ArbitrumDAO](https://dune.com/queries/3480520/5849859)

### Protocol Roadmap

Our roadmap about ArbitrumDAO on-chain voting includes:

**12 weeks after the grant approval**
- Push notifications for on-chain proposals:
  - New Proposal
  - Quorum reached
  - Vote finishes soon
  - Vote finished
- Voting on mobile using a connected wallet
- Linking Snapshot proposals to on-chain proposals
- Visualization of on-chain voting activity:
  - Monthly active users
  - Voters retention
  - Monthly new proposals
  - Percentage of successful proposals
  - Top voters by avg. voting power

**Later**
- Convenience around tokens delegation
  - List of DAO delegates 
  - Delegates' performance visualization
  - Notifications about delegates' activity
- Support of new interfaces
  - Android App

### Audit History & Security Vendors

No.

### Security Incidents

There have been no security incidents to report.

## SECTION 3: GRANT INFORMATION

### Requested Grant Size

60000 ARB tokens

### [Justification for the size of the grant](https://docs.google.com/document/d/1l-gq4HgKlVCAq2QnNCJFA1nHD9mnNg_im1C_XabtA_g/edit?usp=sharing)

The requested grant size will cover the expenses associated with bringing Arbitrum on-chain governance to iOS and iPadOS, including paying the technical team for their work. A detailed breakdown is provided in the linked document.

### **Grant Matching**

We do not have matching funds available.

### Grant Breakdown

- Product & project management, specifications (~240 hours)
- Design & UX tests (~240 hours)
- Backend implementation (~480 hours)
- iOS implementation (~720 hours)

We have estimated an average hourly rate of $80.

### Funding Address

arb1:0xA535473dD8Ce01bAC69Ca33558239dd4435aF705

### Funding Address Characteristics:

2/3 Safe Multisig.
The signing keys belong to two founders and a core team member.

### Treasury Address

No

### Contract Address

No


## SECTION 4: GRANT OBJECTIVES, EXECUTION AND MILESTONES

*Clearly outline the primary objectives of the program and the Key Performance Indicators (KPIs), execution strategy, and milestones used to measure success. This helps reviewers understand what the program aims to achieve and how progress will be assessed.*

### Objectives

- To make ArbitrumDAO on-chain governance accessible on mobile, reaching a broader audience of ARB token holders.
- Bring more users for ArbitrumDAO on-chain voting.
- Increase voter participation and retention rates.

### Execution Strategy

#### **What we are incentivizing**

We incentivize ArbitrumDAO participants to be more active in governance, aiming to increase participation rates and involvement in the DAO's activities.

### **Resources**

**Financial:** We require resources to integrate ArbtirumDAO on-chain voting into Goverland App.

**Marketing:** We need to raise awareness that this feature is available on mobile for ARB token holders.

**Use of funds:** App development & business development.

**Products:** iOS and iPadOS apps with full support for Snapshot and on-chain voting for ArbitrumDAO.

#### Mechanisms for Incentivizing Stickiness

- Push notifications to alert users about votes.
- ArbitrumDAO charts for enhanced insights.
- More engaging governance participation features.

#### KPIs for Measuring Success

- Full support of on-chain voting for ArbitrumDAO within the Goverland App on iOS.
- Increased participation rate among ARB token holders due to activation of a new user group.
  - **Target metric:** 2x in active ArbitrumDAO on-chain voters in 3 months after the integration

#### Grant Timeline and Milestones
    
- **Month 1:** Initial requirements, design, start of technical implementation.
    
- **Month 2:** Design & requirements finalization, first internal release with limited functionality. Continuation of technical implementation.
    
- **Month 3:** Final UX tests, implementation finalization, release.
  
- **Month 4-6:** UX improvements targeting achievements of the target metric: 2x increase in active voters.

#### How the Grant Enables Growth or Innovation within the Arbitrum Ecosystem

Integrating on-chain governance into the Goverland App for ArbitrumDAO will pioneer a new level of accessibility and convenience for ARB token holders, fostering better governance UX, insights, and mobility.

#### Grant Funding Acceptance

Yes, we accept the funding of our grant streamed linearly for the duration of our grant proposal, and the multisig holds the power to halt the stream.

## SECTION 5: Data and Reporting

### Is your team prepared to comply with OBL’s data requirements for the entire life of the program and three months following and then handoff to the Arbitrum DAO? Are there any special requests/considerations that should be considered?

Yes, we are prepared to comply with OBL's data requirements for the entire duration of the program and three months following. We will prepare Dune charts visualizing ArbitrumDAO voting participation using the Goverland App, including charts for target KPIs such as token holder participation rate and voter retention.

### Does your team agree to provide bi-weekly program updates on the Arbitrum Forum thread that reference your OBL dashboard?

While the primary goal of this grant is to integrate on-chain voting into the app, we understand the importance of providing regular updates. Therefore, we agree to provide bi-weekly development progress reports.

### Does your team agree to provide a final closeout report not later than two weeks from the ending date of your program?

Yes, we agree to provide a final closeout report within two weeks from the ending date of our program.

### Does your team acknowledge that failure to comply with any of the above requests can result in the halting of the program’s funding stream?

Yes, we acknowledge that failure to comply with any of the above requests can result in the halting of the program's funding stream.
