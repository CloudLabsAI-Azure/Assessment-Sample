## MetaData
Question Type : Build Tree

## Question
Your organization is using Azure Pipelines and GitHub Actions for CI/CD automation. You are using cloud-hosted build agents as of now; you are asked to change this to on-premise hosted agents to increase concurrency. Match the corresponding solution for Azure Pipelines and GitHub Actions.

## Labels
Label 1 : Azure Pipelines
Label 2 : GitHub Actions
 
## Options
Option 1 : Hosted Build Agents
Option 2 : Self-Hosted Agents
Option 3 : On-prem Runner
Option 4 : Personal Build Agents
Option 5 : Self-Hosted Runner

## Answers
Label 1 : Option 2 : 6
Label 2 : Option 5 : 7
 

## Reference Links
https://learn.microsoft.com/en-us/training/modules/introduction-to-github-actions/8-explore-runners

## Explanation
In Azure Pipelines, if you want to increase concurrency and have more control over the build environment, you can use self-hosted agents. Self-hosted agents are installed on your own infrastructure, either on-premises or in a virtual machine in the cloud. By using self-hosted agents, you can have greater flexibility in customizing the build environment and increase concurrency by adding more agents to handle multiple builds simultaneously.<br>Self-hosted runners are machines that you can host and manage yourself to run workflows in GitHub Actions. These runners can be set up on-premises or in your own cloud environment. By using self-hosted runners, you can have more control over the execution environment and increase concurrency by adding more runners to handle multiple workflows simultaneously.
