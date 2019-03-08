<This document represents a suggestion of the organization of papers describing distributed systems for the audience of the Delta P2P foundation. This is adapted from the Wiegers vision and scope template.>

# Business Requirements

<The business requirements provide the foundation and reference for all detailed requirements development. You may gather business requirements from the customer or development organization’s senior management, an executive sponsor, a project visionary, product management, the marketing department, or other individuals who have a clear sense of why the project is being undertaken and the ultimate value it will provide, both to the business and to customers.>
## Background
<This section summarizes the rationale for the new product. Provide a general description of the history or situation that leads to the recognition that this product should be built.>
## Business Opportunity
<Describe the market opportunity that exists or the business problem that is being solved. Describe the market in which a commercial product will be competing or the environment in which an information system will be used. This may include a brief comparative evaluation of existing products and potential solutions, indicating why the proposed product is attractive. Identify the problems that cannot currently be solved without the product, and how the product fits in with market trends or corporate strategic directions.>
## Business Objectives and Success Criteria
<Describe the important business objectives of the product in a way that is quantitative and measurable. The value provided to customers is described in section 1.4, so this section should focus on the value provided to the business. This could include estimates of revenue or cost savings, return on investment analysis, or target release dates. Determine how success will be defined and measured on this project, and describe the factors that are likely to have the greatest impact on achieving that success. Include things within the direct control of the organization, as well as external factors. Establish measurable criteria to assess whether the business objectives have been met.>
## Customer or Market Needs
<Describe the needs of typical customers or market segments, including needs that are not yet met by the marketplace or by existing systems. You may wish to describe problems customers currently encounter that the new product will (or will not) address and how the product would be used by customers. Identify the customer hardware and software environment in which the product must operate. Define at a high level any known critical interface or performance requirements. Avoid including any design or implementation details. Present the requirements in a numbered list so that more detailed user or functional requirements can be traced to them.>
# Vision Statement
<Write a concise vision statement that summarizes the purpose and intent of the new product and describes what the world will be like when it includes the product. The vision statement should reflect a balanced view that will satisfy the needs of diverse customers as well as those of the developing organization. It may be somewhat idealistic, but it should be grounded in the realities of existing or anticipated customer markets, enterprise architectures, organizational strategic directions, and cost and resource limitations.>
## Major Features
<Include a numbered list of the major features of the new product, emphasizing those features  that distinguish it from previous or competing products. Specific user requirements and functional requirements may be traced back to these features.>
## Assumptions and Dependencies
<Record any assumptions that were made when conceiving the project and writing this vision and scope document. Note any major dependencies the project must rely upon for success, such as specific technologies, third-party vendors, development partners, or other business relationships.>

# Scope and Limitations
<The project scope defines the concept and range of the proposed solution. It’s also important to define what will not be included in the product. Clarifying the scope and limitations helps to establish realistic expectations of the many stakeholders. It also provides a reference frame against which proposed features and requirements changes can be evaluated. Proposed requirements that are out of scope for the envisioned product must be rejected, unless they are so beneficial that the scope should be enlarged to accommodate them (with accompanying changes in budget, schedule, and/or resources).>
## Scope of Initial Release
<Describe the intended major features that will be included in the initial release of the product. Consider the benefits the product is intended to bring to the various customer communities, and generally describe the product features and quality characteristics that will enable it to provide those benefits. Avoid the temptation to include every possible feature that any potential customer category might conceivably want some day. Focus on those features and product characteristics that will provide the most value, at the most acceptable development cost, to the broadest community.>
## Scope of Subsequent Releases
<If a staged evolution of the product is envisioned over time, indicate which major features will be deferred to later releases.>
## Limitations and Exclusions
<Identify any product features or characteristics that a stakeholder might anticipate, but which are not planned to be included in the new product.>

# Architecture
<Define the architecture of the solution, from a 10k feet view to defining the inputs and consumption of the distributed system>
## Architecture diagram
<Declare an architecture diagram for the project. A good rule of thumb is to keep the number of components under 10. For each component, consider having a follow-up paragraph explaining what each component does.>

## Lifecycle diagrams
<Define diagrams representing the lifecycle of the system, usually with sequence diagrams.>
### Data input
<Define a diagram representing how data enters into the system. What data enters the system, when, who pushes the data?.>

### Data consumption
<Define a diagram representing how data will be consumed from the system. Is data pushed to participants, or requested?>

## Data structures
<Define each data structure used by the system to accept input or send data to other peers.>

# Trust
<Define how trust will be managed in the system. It may be that the system will require a shared secret or a registration to a central system.
It's also possible that the system requires presets in place prior to deployment to allow participation.
If the system is an open peer to peer system, please indicate it here.>

## Trust type

## Identity
<Define how the identity of the participants will be managed in the system. It can be a third party database, wallets, key pairs...>

## Incentive disbursement

### Lifecycle
<Define a representation explaining how participants to the system may receive payment for their involvement with the system.
Usually this representation is first a sequence diagram showing the happy path by which incentives are introduced to participants in the system, if applicable.>
### Mitigations
<List each mitigation measure in place making sure the distributed system is able to defend itself against bad incentives, bad actors>

# Attack Mitigations
<List each attack pattern the system is drilling against, explaining how it will perform under a variety of network conditions or in the presence of attackers.
Think of attacks such as denial of service attacks, amplification attacks, discouragement attacks...>
