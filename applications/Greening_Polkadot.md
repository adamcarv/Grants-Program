# W3F Grant Proposal

- **Project Name:** Greening the Polkadot Network
- **Team Name:** Bitgreen Inc
- **Payment Address:** 0x7C9F0962D07AF7EE4A788a1a6576Efb4F121DA3A USDC
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 3
- **Applied Amount:** $200,000

## Project Overview :page_facing_up:

To bolster Polkadot’s current standing as the blockchain network with the lowest carbon footprint, an internal effort 
has been initiated to coordinate capital and resources to extend the network’s leadership in crypt-climate activity. The following
proposal pairs with the recently approved Sequester proposal for a pallet to drive parachain treasury funds to carbon
offset purchases. An integral functional component that must first be resolved is determining the scope, methodology,
measurement parameters, and reporting standard of the electricity consumption and approximate emissions by each
participating parachain. Bitgreen will design this procedure alongside a qualified partner to:

1. Operationalize the methodology for programmatic execution
2. Deliver a dynamic audit dashboard providing ongoing analysis and reporting of the Polkadot ecosystem’s overall
   carbon emission
3. Facilitate the purchase of high quality carbon credits and renewable energy credits

The assessments will be rooted in on-chain and off-chain best practices for emissions auditing, alongside interviews with parachain
stakeholders and a custom carbon accounting framework.

## Introduction

Emissions of anthropogenic greenhouse gasses (GHG) that drive climate change and its impacts around the world are
growing. As a result, the need to accelerate efforts to reduce anthropogenic GHG emissions is increasingly urgent. As
concerns over climate change grow, investors, consumers, regulators (see [SEC, March 2022](https://www.sec.gov/news/press-release/2022-46)) and other stakeholders are increasingly calling for and requiring climate-related disclosures. Research models calculate that 
humanity must remove approximately 22 gigatons of CO2 equivalent (CO2e) from the atmosphere by the year 2030, and annually 
every year thereafter. Since global GHG emissions in 2021 topped 36 billion tons of CO2e, we 
can fairly assume that regulatory scrutiny, mandatory compliance, and consumer discrimination will all intensify in the coming years,
and result in new competitive advantages and disadvantages for companies entrenched in their environmental sustainability.

Blockchains, their decentralized applications and communities are not immune from this standard of
transparency and exposure to reporting. Surging demand for cryptocurrencies and the contentious debate over Proof of Work vs. Proof of Stake has
highlighted the flashpoint issue of blockchain’s growing energy consumption. Therefore it is not surprising to see
several Layer 1 blockchains make net zero commitments (Polygon, Near, Celo, Ripple) or the emergence of initiatives
aiming to set new standards to guide the crypto community towards decarbonization. 

## Existing Methodologies

To date, there has been limited research efforts to develop and use methodologies to effectively quantify the carbon
footprint of blockchain platforms, and even less to quantify greenhouse gas emissions of extensive networks like
Polkadot and make those reports open source and tool-based. Recently, the Crypto Carbon Ratings Institute (CCRI)
developed a methodology to assess the total electricity consumption and total carbon emissions per year of six
proof-of-stake blockchains. Polkadot was shown to have the lowest carbon emissions. Their methodology, however, only
analyzed the electricity consumption by looking at a single node, and used the average grid intensity worldwide. The
authors derived the carbon footprint (tCO2e emissions / year) of the Polkadot network based on these limited
assumptions.

## Carbon Neutral versus Net Zero Carbon

Carbon-neutral means purchasing carbon credits equivalent to emissions released, without the need for emissions
reductions to have taken place. Net-zero means reducing emissions in line with latest climate science, and balancing
remaining residual emissions through carbon removal credits. Net-zero carbon is linked to the Paris Agreement, which
aims to limit the rise in global temperatures below 1.5°C. — a goal that requires more ambition and serious strategy
(and many believe is already out of reach). Ideally, carbon neutrality sits within a robust carbon management strategy. 
While the two concepts are similar, the mainstream view is that Net Zero Carbon is more ambitious than just being Carbon Neutral.

The goal of Net Zero Carbon is to eliminate emissions as much as possible, before using other tactics such as carbon
removal or offsetting. For the Polkadot network, that means investing in energy efficiency, purchasing renewable
electricity (RECs), and/or using zero carbon fuels. With this approach, we first reduce the need to offset or remove
carbon from the atmosphere as much as possible. In contrast to this, Carbon Neutrality does not have the same
requirement to prioritize eliminating emissions at source in the first instance. In recent years, companies have claimed
carbon neutrality by simply compensating all of their emissions with carbon credits or offsets. This approach doesn't
tackle the emissions at source and might not be the most effective strategy to tackle climate change.

## Solution for Polkadot

Blockchain technology doesn’t have to mean environmentally unfriendly. To the contrary, with thoughtful design and
policy choices, it’s possible to merge the effectiveness of immutable, decentralized systems with environmental
responsibility and then channel treasury resources to proactive climate positive initiatives. Bitgreen aims to develop a
cost-effective, relevant and complete way to estimate the GHG emissions of the Polkadot network. At the same time, we
aspire for the methodology to become open source to set a new measurement bar for the industry.

Beginning with the end objective in mind, the final deliverable for this grant proposal is a dynamic dashboard that reveals
periodic reporting of electricity consumption and emissions per participating parachain and the Polkadot and
Kusama relay chains. Some of these parameters are still TBD as we do not yet know precisely what information is
available and the quality or existence of necessary APIs. Upstream from the dashboard will be a database for calculating
the carbon footprint of the validators, collators, and infrastructure units, which together comprise the hardware and
shared computing elements of the Dotsama networks.

### Team members

* CEO, [Adam Carver] (https://www.linkedin.com/in/adamcarver/)
* CTO, Dennis Reichelt
* Marketing, [Alexandra Heller](https://www.linkedin.com/in/alexandraheller/)
* General Counsel, [Jeff Truitt](https://www.linkedin.com/in/carboncryptolawyer/)
* Partnerships, [Gilad Goren](https://www.linkedin.com/in/giladgoren1/)
* Sustainability Metrics & Integrity, [Robin Duchesneau](https://www.linkedin.com/in/robin-duchesneau/)
* Engineering (7): Samuele Lande, Marcos Macedo, Mike Latour, Johannes Ill, Trent Rebeiro, Timothee Vialatoux, Stanly
  Johnson

### Contact

- **Contact Name:** Adam Carver
- **Contact Email:** adam@bitgreen.org
- **Website:** https://bitgreen.org

### Legal Structure

- **Registered Address:**
- **Registered Legal Entity:** Bitgreen, Inc. Delaware C corporation filed September 10, 2021

### Team's experience

Bitgreens Robin Druchsenau has long experience in auditing carbon sequestration methodologies during his previous work
for Sustain Cert. 

Bitgreen is part of the Polkadot builders program and applied for another currently active grant "Bitgreen Carbon
Tokenomics"

### Team Code Repos

- [Bitgreen](https://github.com/bitgreen)
- [Custom Browser Wallet](https://github.com/bitgreen/browser-wallet)
- [Parachain](https://github.com/bitgreen/bitg-node)

### Team Members

- [Samuele](https://github.com/orgs/bitgreen/people/samuelelandi)
- [Trent](https://github.com/orgs/bitgreen/people/trentrebeiro)
- [Mike](https://github.com/patedetomates)
- [Stanly](https://github.com/abhath-labs)
- [Johannes](https://github.com/orgs/bitgreen/people/Ulltra7)
- [Timothee](https://github.com/needs)
- [Vlada](https://github.com/rappix)

## Development Status :open_book:

The Bitgreen [Parachain](https://github.com/bitgreen/bitg-node) is well under development and the ecosystems first
product is in the final stage of development and due to release fully in Q3 2022.

## Development Roadmap :nut_and_bolt:

### Overview

* Total Estimated Duration: 4 months
* Full-time equivalent (FTE): 4 full-time
    * A subject matter expert to identify and implement the right policy and lead the project
    * An Auditor will need to conduct research on individual parachains
    * A blockhain/full-stack engineer is required to extract data from the network and transform it into a common data
      model to use as inputs
    * 2 Frontend Engineers will be needed in the later stages of the project

### Milestone 1 Example — Initial Research & Written Model

- **Estimated duration:** 4 month
- **FTE:**  4
- **Costs:** 200,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0  |
| 0b. | Documentation | We will provide both **inline documentation** of the code and extensive module documentation. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Article | A report on the methodology and relevant research will be published |
| 1a. | Literature Review | Bitgreen will review the literature to determine the current state of the market in terms of scientific research, strategies and quantification approaches used to quantify GHGs of crypto & blockchain platforms, data availability, and proposed governance frameworks and/or standards for offsetting and/or reducing carbon-related impacts. The review will focus on GhG emissions from electrical use. |
| 1b. | Kick-off | Bitgreen will identify potential Polkadot network stakeholders, provide materials, and conduct meetings to present the project activities and anticipated levels of involvement required. This will include selected members of Parity, selected Parachains, and external subject-matter experts. Bitgreen will prepare powerpoint slides and host various kick-off sessions. |
| 1c. | Information & Data Acquisition | Bitgreen will conduct interviews with identified key persons. The purpose is to collect information on how the different parachains conduct their operations, determine the availability of the data that is required to estimate GHG emissions from electricity consumption. |
| 1d. | Analysis & Calculation | Once Bitgreen has collected data from the Polkadot network members, including the information and data from the literature review, a fit-for-purpose carbon accounting framework will be designed.  |
| 2a. | On-Chain Data Gathering | Data from the network needs to be gathered on state and amount of validators, peer lists to determine where on the globe validators are located, how many additional full nodes and clients are in the network |
| 2b. | Data Transformation | A tool to transform the gathered data into GHG estimates based on the 1d. developed Methodology needs to be implemented | 
| 2c. | Dashboard | A Dashboard needs to be implemented that shows the state of the networks electricity consumption and GHG emissions. The data will not be current state data but snapshots likely to be done every 6 hours. The dashboard could be broken down by Parachain. This might not be advisable though information about infrastructure is gathered that might be sensitive. |
| 2d. | Dashboard Admin | Since the state of the network changes especially on additionally run infrastructure machines that are not visible in the peer list parachain teams need to be provided with an updatable easy to use form to gather this additional infrastructure |

