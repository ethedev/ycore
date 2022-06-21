# Yam Core Development

Sirs, ladies and gents, this post is for upcoming work establishment and improvements to the yam protocol, it consists of developments, deployments, maintenance and related operations at yam.

@e: I have been leading the work on a range of initiatives at yam for the past year from development planning to execution, code reviews, websites and smart contract developments, updates and deployments, building interfaces, tooling, organizing and operating engineering and service funds, reimbursements and contributors payouts, contributors onboarding and support, communications with partners and other parties, infrastructure stability and maintenance. With thanks to all the contributors that i have worked with, even with the challenges we had, we developed, experimented, learned and got to where we are at yam with your help and contributions, i hope you will continue contributing adding more value on yam in the future.

Currently there are multiple things i see the need to focus on for adding value to the success of yam on the top of the maintained stability we have as a protocol.

I will ensure and focus on the release of an upgraded yam core, additional protocol features, improvements and deployments after audits, new yam website with maintenance, new api releases and upgraded tooling, maintaining infrastructure, coordinating security and managing the mentioned points for the next year.

# Protocol Mission

We want to get back the value that yam originally had on its launch, and surpass it bringing back community and a gradually increasing token holder base, adding multiple features beyond the current governance function to the yam protocol.

> Yam DAO is a self governed community building integrated and novel DeFi products designed to grow the value of the Yam ecosystem. Empowered by shared economic incentives in pursuit of a decentralized self sovereign financial system for all.
> 

# Fast Forward, History and Future Goals

Yam started the “DeFi Summer” and its big wave, which many joined with yield farming but that’s not necessarily going in the same path as to what it offers, we still have the [farming function](https://yam.finance/#/farm) but we have bigger goals. As we have experimented and discovered while building on multiple features and projects, the plan is to continue supporting good ideas, adding functionality and value to the token, to then distribute profits we are gaining to the token holders, getting yam into a wider range of audience, keeping everything fully governed and decentralized.

# Planned Improvements

## Development

- **Protocol Restructure: Contracts - [Devdocs](https://github.com/ethedev/yam-dev-docs/blob/master/yam-contracts.md)**

    **Description:** The protocol had two migrations in the past as well for how its mechanism work, with then turning off the rebase, which plays a big part in the conversion of the numbers in the protocol, even though the core and governance has been maintained and secure to date, it was not very simple if you are a developer or an enthusiast to get yourself familiar with how everything work in accordance to each other, specially on a smart contract level and its little available documentation. That aside, everyone sees how many changes happened on defi in terms of scalability, in specific speaking about general layer 2 focuses and high gas prices on the ethereum mainnet, thats one of the things that can be dealt with. (**Read more on Yam Multichain [here](https://docs.google.com/document/d/1umm0Mf3FufHO7DDNBzCA5ELPl2FnCxsaHcFTnRaXLAI)**)
    
    **Plan:** Reconstruct all existent, relevant and focus on creating new contracts, with what i have started working with **[here](https://github.com/ethedev/protocol)**. Contracts are undergoing major changes, while it will still essentially work to what we have currently related to governance. Major changes will include Governance upgrade, Token upgrade with delegation, Multichain implementation (to Optimism, Arbitrum and other chains), Protocol bridges (network specific), Treasury upgrade, Proxy modular functionality controlled by governance and a migrator. Audited and open source contracts libraries will be used, for example to Compound and OpenZeppelin, with more to be considered moving forward.
    
    ***Features remaining with the new deployment:***
    
    - Governance and voting token.
    - Token holders controlled treasury.
    
    **Timeline:**
    
    1. **Development**
    2. **Development Testing**
    3. **Public Testing**
    4. **Audit and Selections**
    5. **Deployment**
    6. **Previous to New gov access**
    7. **Unlock Migrator, Migration Announcement, Migrate!**
    8. **Announcement**
    9. **Maintenance**
- **Protocol Restructure: Website - [Devdocs](https://github.com/ethedev/yam-dev-docs/blob/master/yam-website.md)**
    
    **Description:** The yam website will be the place to go to, for any user in need of information about yam as well to interact with the protocol, where they will have access of multiple pages for doing so.
    
    **Plan:** Website will include everything we have currently and more to fulfill the needs of the newly developed contracts and tools use. Consisting of an informational landing page, a governance page that will display the onchain proposals as well to the possibility to create a simple proposal if you have the minimum tokens, a treasury page that shows the different balances of tokens owned by the treasury with charts and related statistics, a user page to show what the user has of yam tokens or any other yam project tokens, and a farm page showing clearly what we have to interact with and the how-to for accessibility. It will undergo an upgrade as well to a restructure, using the tools that we have and will be building such as the yam sdk, subgraph and api.
    
    - **Sitemap (Base)**
        - **Landing**
        - **Governance**
            - **Vote**
        - **Treasury**
            - **Statistics**
        - **Tools**
        - **Docs**
    - **Sitemap**
        - **Landing**
        - **Governance**
            - **Vote**
            - **Proposal**
        - **Treasury**
            - **Statistics**
        - **Farm**
        - **Projects**
        - **Tools**
            - **SDK**
            - **API**
            - **Subgraph**
        - **User**
        - **Docs**
- **Yam SDK - [Devdocs](https://github.com/ethedev/yam-dev-docs/blob/master/yam-sdk.md)**
    
    **Description:** The Yam SDK will be one of the tools used by multiple parties and dapps, its purpose is to make developers interact with yam easier. Main use will be on the yam website for features and interactions with smart contracts, and generally for any party interested in yam read/write data.
    
    **Plan:** SDK to include everything you need related to yam, yam smart contracts interactions, with further helper functions as well to wrappers related to yam projects. It will interact programmatically with off-chain and on-chain data, with different public and private APIs, smart contracts and other tools we are building such as the yam subgraph.
    
- **Yam API - [Devdocs](https://github.com/ethedev/yam-dev-docs/blob/master/yam-api.md)**
    
    **Description:** The Yam API will help save and collect special data, having historical data as well to specific endpoints for different data collection related to yam. It will serve the website mainly and other 3rd party applications.
    
    **Plan:** Yam API will include different data endpoint groups, from: yam historical data, treasury data, a wrapper for yam smart contracts basic read functions, a section of helper endpoints and other needed relevant endpoints overtime. The API also aims to deliver data in a more decentralized way, and thats one of the things that will be the focus on to achieve.
    
- **Yam Subgraph - [Devdocs](https://github.com/ethedev/yam-dev-docs/blob/master/yam-subgraph.md)**
    
    **Description:** The Yam Subgraph will be used as a way to query what that the yam smart contracts entails with ease, it will be used for specific calls through the API, the SDK and other places as well to 3rd party applications. As described: where all data is stored and processed on open networks with verifiable integrity, the yam subgraph will makes querying its data fast, reliable, and secure.
    
    **Plan:** Yam Subgraph will cover the yam smart contracts read functions and events, with additional interesting data for collection, such as user, token and governance data relations.
    

### *See development documents for further information.*

## Deployment

**Contracts:** Working with bleeding edge technology with some material that auditors have no yet full reach on, will require a good amount of testing pre and post audits making sure everything is fully functional before moving into production, once the development is finished with major testing coverage, deployed and tested on test networks, we will move into next phase deploying on the main networks, such as Ethereum Mainnet, Optimism, Arbitrum, Polygon or other, this will be voted on.

**Website:** After development finalization, deployment will be split into 2 phases (except to small changes or critical bug fixes). The phases are testing build and live build, the testing build will undergo tests from the community and anyone interested, making sure everything is working, then it will be deployed live. As well on each deployment prepared automated tests will make sure things are working perfectly.

**SDK, API, Subgraph:** Having as much test coverage as possible. Will also be split into 2 phases, with automated tests running pre live deployments and releases approvals.

## Security

**Governance:**

- **Current:** Governance is in good stand, guardian is set in place to protect against any malicious attacks. Moving into the future: a process and a proposal that will outline different options to be chosen from, will be written and decided upon to how we will migrate this on release of the contracts upgrades.
- **Multichain:** Each network will have a signing mechanism that will be required to always be signed for the network governance to work and be included, this will act as another layer of protection to block wider range of malicious attacks against the protocol.
    - Guardian will also be able to decline any cross networks malicious actions.

**Bug Bounties:** A security document of which the critical bugs will fall under, will be posted in the near future, and will include a section detailing what is covered and what the bug bounties to be valued at. A proposal will also be written and proposed for signaling on snapshot to confirm the numbers and final details.

## Maintenance

Maintaining code and bug fixing is key for a better product, that will be focused on as well to having the website, api, code, tooling and everything else we develop, working as described in its own repos, for things to be online and serving the users. Target is to maintain stability. Development will go through updates and bug fixes with additional features support and changes that we see fit to make products better. Documentation is also to always be maintained.

## Contributors

- Currently working with 6+ developers and 2 designers that i am planning to hire, as well to more devs and relevant contributors in Q4 of this year.
- Additionally bounty based work tasks are posted with more to come.

# Timeline

## Q3 2022

**Public**

- **Upgraded Yam Contracts**
- **Yam Protocol:** Multichain Governance (Alpha)
- **Yam Slick New Website (Static)**

**Work In Progress**

- **Contracts:** Upgraded Contracts, Basic Multichain Governance
- **Websites:** Website Design, Website Base, Partial Network Connections, Partial SDK and API Integrations
- **Infrastructure:** SDK API Subgraph Base Structure, SDK Testnet Contracts Connection, SDK Basic Subgraph Integration, API Partial Endpoints Connections

## Q4 2022

**Public**

- **Yam Protocol:** Multichain Governance (Testing)
- **Yam Slick New Website (Testing)**
- **Website Proposal Page (Current Interact)**
- **New Tooling:** SDK
- **Snapshot:** Signaling for L2 Networks

**Work In Progress**

- **Contracts:** Multichain Governance, Testnet Deployments and Interactions
- **Websites:** Website Static Interactions, Proposal Page Design, User Page Design, Network Connections, SDK and API Integrations
- **Infrastructure:** SDK and API Website Integration, Contracts Coverage, Fallbacks Subgraph Integration, Partial Test Coverage, Partial Developer Docs, API Security, Subgraph API Integration, Partial Test Coverage, Partial Developer Docs

## Q1 2023

**Public**

- **Contracts Audits**
- **Launch Potential**
- **Yam Protocol:** Multichain Governance (Mainnet, Multichain)
- **Yam Slick New Website (Multichain)**
- **New Tooling:** API, Subgraph
- **Snapshot:** First Secondary Network
- **Snapshot:** Bug Bounty

**Work In Progress**

- **Contracts:** Audit Contracts, Audit Corrections and Testing, Partial Developer Docs
- **Websites:** Manual Testing, Updates, Partial User Docs
- **Infrastructure:** SDK Manual Testing, Automation, Tests Coverage, Developer Docs, API Partial Test Coverage, Partial Developer Docs, Subgraph Automation, Tests Coverage, Developer Docs

## Q2 2023

**Public**

- **Snapshot:** Second Secondary Network

**Work In Progress**

- **Contracts:** More Explorations, Developer Docs
- **Websites:** User Onboarding, Projects Page Design, Developer Docs
- **Infrastructure:** SDK Projects Structure, Linked Distribution Assistance, API Data Decentralization, Manual Testing, Tests Coverage, Developer Docs, Subgraph Maintenance, Updates

## Q3 2023

**Public**

- **Advanced Planning**

**Work In Progress**

- **Contracts:** Maintenance, Accounting for Updates
- **Websites:** Maintenance, Accounting for Updates
- **Infrastructure:** Maintenance, Accounting for Updates

## **Notes**

- Relevant snapshot proposals will be created every time we need further vote and signaling.
- Everything mentioned here is to be achieved and already in progress under development, although keep in mind some things can probably change or be different as we progress more into the future. Such will reflect changes on the development documents and in the documentation of the repositories related.

# ❤️🌊🍠

Looking forward and very excited for stable, secure, modular and solid standing structure of a core with fine contracts, websites and tools, to lead by example as what always yam was to other DAOs projects, and for anyone else interested with starting their own!

**See you on other chains.**

**E.**

*Please note, timelines are yet to be finalized and will be ready shortly!*
