# SEV-xxxx: [Name]
[Date Written]

*Incidents in this organization are tracked as SEVs, or System EVents. These documents serve as a record of the people
involved in the detection/resolution of these events, as well as technical/internal details, to serve as a permanent
reference for the team for future process improvement or training.*

*These are intended to be living documents where possible- as additional details are uncovered, they should be added to
this document and relevant findings updated.*

* **Level:**

    *Choose a level based on the final impact of an incident. For instance, a SEV might start out as a **3** for a
    migration but end up as a **1** when an issue arises during the maintenance window. Use your discretion, but prefer
    to choose a more impactful choice in ambigous situations.*

    * 1: User-Visible Production Impact
    * 2: Non-User-Visible Production Impact, or User-Visible impact in lower environments
    * 3: Informational/Proactive

* **Discovery:**

    *Choose a method by which the incident came to the attention of the team. These methods are mutually-exclusive.*

    * Alerts: A health monitoring system noticed a failed check.
    * Aliens: Happenstance (luck) contributed to a team member noticing the error.
    * User Reports: An external party notified of a failure that was not caught by other means.
    * Review: A structured code/process review caught the issue.
    * N/A: The incident is proactive or did not involve any of the other methods.

* **Areas Affected:**
  
  * *List any parts of the system/organization that required resolution steps here.*

## Responders
*List all of the parties who responded to this incident, or contributed to its discovery/resolution in some way. At the
minimum, an **IC (Incident Commander)** should be listed who was responsible for coordinating resolution efforts
as well as compiling this document. Other useful roles to list would be **Legal** or **Technical** counsels that assisted
in resolution.*

> [!IMPORTANT]
> ***Do not use this to assign blame to someone for causing the incident in the first place.***

* **IC:** [Person 1](link)

## Abstract
*Include a single paragraph summarizing the events in the timeline, as well as their impact on the organization/systems involved.*

## Timeline
*Provide a timeline that lays out the major events of the SEV, with as accurate timing as you can. The "gap" column should
provide a sense of how long it took between these major events, which can often indicate areas for improvement in response time.*

| Date/time |  | Event |
| --------- | --- | ----- |
| 2024-05-27 12:00:00am PST | - | First event. |
| 2024-05-27 12:01:00am PST | 1 minute later | Second event. |
| 2024-05-28 8:01:00am PST | 1 day, 8 hours later | Third event. |

## Review
*Go into detail on what happened during the incident, as granular as possible. Include notes and findings from the review meeting(s).*

> [!IMPORTANT]
> ***Although specificity is important, avoid placing blame for an incident on a single person or group.**
> Much as we all enjoy the benefits of our work, so too do we all share responsibility for that work's failures.
> Reviews that call out others for blame do little more than create a culture of fear and resentment, and obscure cultural
> failures that allowed the inciting mistakes to be made in the first place.*

## Next Steps
* [ ] List action items (preferably with links to tickets where available) that are needed to resolve this issue long-term.