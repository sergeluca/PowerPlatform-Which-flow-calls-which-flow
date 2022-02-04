# **Welcome to the Power Platform "Which flow calls which flow" utility**

## Overview 

This small utility has been created by **Doctor Flow** aka **Serge Luca** from [Power Platform Associates](https://www.shareql.com).

The goal of this utility is to provide a way to figure out which (Microsoft Power Automate) flow is invoked by which flow and which flow calls which flow.
Indeed some applications (like the BPM Toolkit on Github) can have hundreds of Power Automate flows, that call each other.

During the deployment of such solutions, the child flows must be activated before the parent flows.
Also as a developer, it is important to know the impact of modifying an existing flow: which parent flow will be impacted?

So this is what the utility display 

In the following picture, you can see on the left side the parent flows and the child flows on the right.

Typically the flow "BPM Toolkit - Case Launcher v2" calls 8 flows directly.

![](https://github.com/sergeluca/PowerPlatform-Which-flow-calls-which-flow/blob/main/Images/flowcallsflow.jpg)



The other picture illustrates the parent flow of a specific flow: as you can see the flow BPM Toolkit - Log Flow error is called by many flows.

![](https://github.com/sergeluca/PowerPlatform-Which-flow-calls-which-flow/blob/main/Images/flowiscalledby.jpg)

## How can you install this utility ?

Watch the following [video](https://youtu.be/3yJpoFH0DP8)




