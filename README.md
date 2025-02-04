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

#### Problem: Slow and Restrictive Software Approval Process

Tasks:
- Automate approval workflows where possible
  - Introduce a pre-approved software list to eliminate repetitive approvals.
  - Create IAM roles with specific authorizations (as done in R&D)
- Rethink approval workflow: Delegate approval for specific categories of software to tech leads who understand developer needs.

Expected outcome


#### Improve Developer Machines
- Re-assess "heavy" softwares that are making the machines slow and remove them for users that dont need them (?)
- Upgrade development machines for frequent developers (16GB RAM and 16-core CPUs )

### Phase 2: Mid-term actions 

#### Set up a framework for testing and updates 
- Implement Staging Environments for Updates
- Require Software Owners to maintain up-to-date test suites for their software
- Introduce a mandatory staging environment to test software updates before deployment.
- Implement a “No Untested Updates” policy for Software Owners.

#### Promote on-cloud environment
- Start assessing which projects/developers can move to the cloud environemnt

### Phase 3: Long-term actions

#### 


#### Move selected projects to cloud environment
- Transition projects into the Data Platform according to use case squad availability
- Establish clear guidelines for when to use on-premises vs. cloud environments


👀 [Backlog](https://github.com/users/catarinapmartins/projects/2/views/1)

## Expected Outcome

- Faster approvals → Reduced waiting times, improved developer satisfaction.
- Better performance → Faster machines, fewer delays.
- More stability → Software failures decrease with enforced testing.
- Increased accountability → Software Owners take responsibility for their products.
- Greater cloud adoption → Reduced reliance on restrictive on-prem environments.


## Next steps


