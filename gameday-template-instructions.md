This is a companion document to the [gameday template](gameday-template.md)​. 
Here you’ll find a more detailed explanation of each section and my intention for it. 

Generally, create a copy of the ​[gameday template](gameday-template.md)​. 
Duplicate then increment the Scenario 1: section for as many scenarios are you’re planning. Then update any of the areas between < >s. Feel free to modify your copy to suit your needs. The other areas should be completed by the Outcome Recorder during the gameday or shortly after. 
When filling in your copy of the template keep in mind your audience to be sure you’re including relevant information to them.

## Overview
This section should provide readers and participants an overview of what the gameday is intended to accomplish or test.
Some questions to get populate this section could be:
* What are the goals in mind?
* What assumptions do we have about the thing(s) (service, code, tool, network, etc)?
* How do we the thing will recover? Can it self heal or will we need to intervene?
* Has there been an outage or change lately that could change the things we know about the thing?

## Communication Channel(s)​: 
< slack room, video conferencing, etc> If you’re going be using a specific room in slack or a video chat for the communication channel include it here so participants will know where to gather.

## Participants

Navigator :​ This person will guide the gameday and be the incident commander if you require that. 
They'll keep things on task, make sure steps are completed (in order) and do any necessary communications.

Driver :​ This person will perform the gameday tasks defined in the scenarios.
Sometimes this is multiple folks if there are permissions or different duties assigned to differnt teams.

Outcome Recorder:​ This person will record the outcomes and follow-up items in your copy of the template being used for the experiment.

Feel free to add additional roles here like a timekeeper or charts master. Ideally, these are decided before the gameday begins.

## Pre-Gameday Tasks
* List any tasks which can be done in advance and can be queued up. These tasks might include writing code that will need to be deployed for the gameday, setting up a proxy, configuring a Gremlin attack, writing scripts, answering architecture questions, etc.
* List any tools or tasks which should be tested in advance Setup Tasks
* List the tasks to get the game day set up. Generally, these will be tasks happening ​just before beginning ​your first scenario. This could be things such as deploying a gameday version or branch of code, beginning Gremlin attacks, enabling a proxy, running scripts, clearing caches, etc.

## Scenario 1: Clever Scenario Title
Include a detailed description of your scenario. Explain the actions which will be performed in a way your audience will understand. 
A good description will also include some reasoning behind scenario and what you hope to learn.

### Expected Outcomes
Note what you think will happen during the scenario. Do you expect to get paged? If so, which alert(s) wil be triggered? Do you expect customer impact? If so, to what extent? It’s also possible you’re not sure because of changes, taking ownership of something new, if that’s the case use the information you have to make the best guess.
Operational Tasks
1. List steps and explicit instructions and commands which will be performed. These instructions should allow the Driver to be able to use them like a runbook. Include commands that will need to run, instructions for tools needed and how the user will interact with them. When including commands, make them easily copy and pastable.

### Verification Methods
* How will we confirm our assertions are true or false, or derive results? This could be alerts triggering, reviewing dashboards, NRQL queries, etc.
* Include links to any dashboards or monitoring

### Actual Outcome
* Update this during the gameday to record what's happening. Things to consider including: dashboard used, screenshots, was someone paged or not paged, how  resource were impacted by the experiment.

### Lessons Learned
* Update this at the end of the scenario or at any point when there’s learning to be noted. Capture details about answers to any questions you had before or during the gameday, if assumptions were accurate or not, etc.

### Post Gameday tasks
* This should be like the Operational tasks section for returning things to pre-gameday state. Rollback and temporary code changes or deploys, remove proxies, make sure Gremlin attacks are wrapped up, etc.

### Follow-up Actions
* This section should be used to capture work the team will want to do later. These could be things like a bug, new risks, mitigated risks, a gap in monitoring, alerting or metric reporting you’ve identified during the gameday, etc. It’s a good idea to either assign this tasks to someone or add them to JIRA or wherever your team tracks work to ensure they don’t die a lonely death in your document.