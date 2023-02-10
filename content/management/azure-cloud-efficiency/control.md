# Control Costs
#### [prev](./optimize.md) | [home](./readme.md) | [](./tuning.md)

When thinking "how can I lower my Azure monthly costs?", two available resources that cannot be forgotten are the **Reserved Instances** and the “new” **Savings Plans** offerings. These two will be important additions to your toolbelt when the goal is to bring significant savings. Cherry on the cake? If your organization already has an active Software Assurance (SA), you can also benefit from licensing cost savings through the Azure Hybrid Benefit (AHUB).

Let's explore each one of them.

## Reservations & Savings Plans

Azure provides you with two ways to save on your usage by committing for one or three years. You have the freedom to choose the savings options that best align with your workload patterns.


### Comparing Reservations with Savings Plans

With reservations, you commit to a specific virtual machine type in a particular Azure region. For example, a D2v4 VM in Japan East for one year. With an Azure savings plan, you commit to spend a fixed hourly amount collectively on compute services. For example, $5.00/hour on compute services for one year. Reservations only apply to the identified compute service and region combination. Savings plan benefits are applicable to all usage from participating compute services across the globe, up to the hourly commitment.

**When to choose Reservations:** For highly stable workloads that run continuously and where you have no expected changes to the machine series or region, consider a reservation. Reservations provide the greatest savings.

**When to choose Savings Plans:** For dynamic workloads where you need to run different sized virtual machines or that frequently change datacenter regions, consider a compute savings plan. Savings plans provide flexible benefit application and automatic optimization.

Walkthrough/demo:  

- [Choose what kind of reservation to purchase](https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/determine-reservation-purchase#recommendations-in-the-azure-portal)
- [View reservation utilization](https://learn.microsoft.com/en-us/azure/cost-management-billing/reservations/reservation-utilization)
- [Decide between savings plans and reservations](https://learn.microsoft.com/en-us/azure/cost-management-billing/savings-plan/decide-between-savings-plan-reservation)


## Azure Hybrid Benefit

Azure Hybrid Benefit is a licensing benefit, and it works by letting you use Software Assurance-enabled Windows Server and SQL Server licenses, and RedHat and SUSE Linux subscriptions on virtual machines in Azure in order to avoid monthly licensing charges. 

Walkthrough/demo: 

- [AHUB Savings Calculator](https://azure.microsoft.com/en-us/pricing/hybrid-benefit)
