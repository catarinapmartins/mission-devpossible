# 🚀 Mission: DevPossible
"Making on-premise development faster, smoother, and (slightly) less painful!"

This repository is the command center for transforming Swissgrid’s on-premises development environment. From streamlining approvals to boosting machine performance, we're tackling the biggest dev headaches with practical solutions. 

## Context

<img width="605" alt="image" src="https://github.com/user-attachments/assets/9b6bf099-5c5c-484b-ba20-05aa5cf227d9" />

## Critical Issues / Key Challenges

- Slow and Restrictive Software Approval Process
- Slow Development Machines
- Frquent Software Failures
- Lack of Software Ownership

## Prioritized Solutions

The distribution of solutions in the different phases considers a balance between the impact on users and implementation time.

### Phase 1: Short-term actions

#### Improve Software Approval Process

Proposed Solutions:
- Automate approval workflows where possible
  - Introduce a pre-approved software list to eliminate repetitive approvals.
  - Create IAM roles with specific authorizations (as done in R&D)
- Rethink approval workflow: Delegate approval for specific categories of software to tech leads who understand developer needs.

Expected outcome: 
- Reduced waiting time for approvals → improved developer satisfaction
- Reduction is administrative tasks for managers


#### Improve development machines

Proposed solutions:
- Upgrade development machines for frequent developers (16GB RAM and 16-core CPUs)
- Re-assess "heavy" softwares that are making the machines slow and remove them for users that dont need them (?)

Expected outcome:
- Better performance → Faster machines, fewer delays.


### Phase 2: Mid-term actions 

#### Improve Software Testing 

Proposed solutions:
- Introduce a mandatory staging environment to test software updates before deployment.
- Implement a “No Untested Updates” policy for Software Owners.

Expected outcome:
- More stability → Software failures decrease with enforced testing.

#### Promote on-cloud environment

Proposed solutions:
- Start assessing which projects/developers can move to the cloud environemnt.

Expected outcome:
- Users become more aware of cloud computing possibilites


### Phase 3: Long-term actions

#### Increase Software Ownership & Set Up a framework for testing

Proposed solutions:
- Define clear ownership, ensuring each software owner commits to testing updates before deployment.
- Require Software Owners to maintain up-to-date tests for their software.
- Introduce automated testing as part of the CI/CD process.

Expected outcome:
- Increased accountability → Software Owners take responsibility for their products.

#### Move selected projects to cloud environment
- Transition projects into the Data Platform according to use case squad availability
- Establish clear guidelines for when to use on-premises vs. cloud environments

Expected outcome:
- Greater cloud adoption → Reduced reliance on restrictive on-prem environments.

## Next steps

- Discuss action plan with management team
- Discuss proposed solutions with technical/implementation team
- Set clear milestones and KPIs for each solution
- Implement changes incrementally, starting with quick wins (Phase 1)
- Regularly gather feedback from developers and iterate on solutions
- Provide training and documentation for new processes and tools


👀 [Backlog](https://github.com/users/catarinapmartins/projects/2/views/1)


