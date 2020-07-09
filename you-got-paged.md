### So, you got paged. ###
1. Don't panic
1. Acknowledge the page.
1. If at any point you aren't sure what to do, ask for help by paging someone else on the team.
    * You can reassign an incident using the PagerDuty app or by creating a new incident
1. Check for other open incidents in PagerDuty which could be related
1. Check for [scheduled changes or deploys](https://) for recent changes which could be related
1. Check the [#slack-channel](https://) for activity or incidents which could be related.
1. Decide if you need to start an incident
 
### Gather information ###
1. Figure out what's paging and why
    * Review the page you received for relevant details - if it's not clear be sure to note this info for the retro
1. Review dashboards and monitoring for the paging service
1. If your incident doesn't seem to be related to an ongoing problem, [start an incident and become the Incident Commander](https://).

### Form a hypothesis based on the symptoms ###
This is a recursive process. You will be asking and answering "why is XYZ happening?" repeatedly until you arrive at some kind of root cause.
 

###### Common symptoms and causes ######

|Symptom|Identified by|Typical cause(s)|
|---|---|---|

### Take corrective action ###
If the root cause is related to a more general problem then you're basically on standby until it is fixed.
 
|Root cause|Corrective action|
|---|---|

 
### Service runbooks ###
  * Are located [here](https://) < This can be a link to a repo of runbooks or individual runbooks > 

### Watch stuff recover ###
Once the issue is fixed, make sure all of our team's services recover. You should see symptoms disappearing on the related dashboards. Alerts will auto-close a few minutes after things are fully recovered.
 
Take notes on what happened for later discussion or a retrospective.
 
### Go back to bed ###

You're done. During business hours you'll discuss the incident with the rest of team, and together you'll figure out what followup actions to take. For now, the incident is over and you have no further responsibilities (unless you get paged again).