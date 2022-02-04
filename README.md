Welcome to the Power Platform "Which flow calls which flow" utility.

The goal of this utility is to provide a way to figure out which (Microsoft Power Automate) flow is invoked by which flow and which flow calls which flow.
Indeed some applications (like the BPM Toolkit on Github) can have hundreds of Power Automate flows, that call each other.

During the deployment of such solutions, the child flows must be activated before the parent flows.
Also as a developer, it is important to know the impact of modifying an existing flow: which parent flow will be impacted?

So this is what the utility display 

In the following picture, you can see on the left side the parent flows and the child flows on the right.

Typically the flow "BPM Toolkit - Case Launcher v2" calls 8 flows directly.

![](https://github.com/sergeluca/PowerPlatform-Which-flow-calls-which-flow/blob/main/Images/flowcallsflow.jpg)


How can you install this utility ?

1. You need PowerBI desktop on your machine
2. You need an environment with a Dataverse database and a premium account.
3. You just need to upload the solution **WorkflowCallsWorkflow**
4. Run the flow WCW utility
5. Depending on the number of flows in your environments (across several solutions), it can take several minutes to complete.
6. Then download the **FlowsCallsFlow.pbix** file

The other picture illustrates the parent flow of a specific flow: as you can see the flow BPM Toolkit - Log Flow error is called by many flows.

![](https://github.com/sergeluca/PowerPlatform-Which-flow-calls-which-flow/blob/main/Images/flowiscalledby.jpg)





