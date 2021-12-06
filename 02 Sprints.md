# Sprints

- Sprint is a short, timeboxed period when a scrum team works to complete a set amount of work
- With scrum, a product is built in a series of iterations called sprints that break down big, complex projects into bite-sized pieces
- Sprints make projects more manageble, allow teams to ship high-quality work faster and more frequently, and gives them more flexibility to adapt to change
- Agile is a set of principles and Scrum is a framework for getting s#it done
- Sprints help teams follow agile principle of "delivering working software frequently" as well as live the agile value of "responding to change over following a plan"
- Scrum values of transparancy, inspection, and adaption are complementary to agile and central to the concept of sprints

Scrum guide
<https://scrumguides.org/scrum-guide.html>

# Plan and Execute scrum sprints

- Sprit Planning
- Daily Scrum
- Sprint Review 
- Sprint Reto

## Sprint Planning
- Sprint planning is a collaborative event where the team answers two basic questions
  1. What work can get done in this sprint?
  2. How will the chosen work get done?
- Choosing the right work item for a sprint is a collaborative effort between the product owner, scrum master, and development team
- Product owner discusses the objective that the sprint should achieve and the product backlog items that, upon completion, would achieve the sprint goal.
- Team then creates a plan for how they will build the backlog items and get them "Done" before the end of sprint.
- The work items choosen and the plan for how to get them done is called the __sprint backlog__.
- By the end of sprint planning the team is ready to start work on the sprints backlog, talking items from the backlog, to "In-progress" and "Done"
- During a sprint, the team checks in during the daily scrum, or standup, about how the work is progressing. The goal of this meeting is to surface any blockers and chalenges that would impact the teams ability to deliver the sprint goal.
- After a sprint, the team demonstrates what they've completed during __sprint review__. This is teams opportunity to showcase their work to stakeholders and teammates before it hits production
- Finally __sprint retrospective__ where teams identify areas of improvement for the next sprint.

# Do's and Don'ts 

## Do:
- Make sure team sets and understands the sprint goal and how success will be measured. This is key to keeping everyone alinged and moving forward toward a common destination.
- Do ensure you have well grommed backlog with your priorities and dependencies in order. This can be a big challenge that could derail the process of it's not properly managed.
- Ensure you have good understanding of velocity, and that it relfects things like leave and team meetings
- Do use of sprint planning meeting to flesh out intimate details of the work that needs to get done. Encourage team members to sketch out tasks for all stories, bugs, and tasks that come into the sprint.
- Leave out work where you won't be able to get the dependencies done, like work from another team, designs, and legal sign-off.
- Finally, once a decison or plan is made, make sure someone captues, that information in your project management or collaboration tool, like Jira. 

## Don't:
- Don't pull in too many stories, overestimate velocity, or pull in tasks that cannot be completed in the sprint. You don't want to set yourself or your team up for a failure.
- Don't forget about quality or technical debt. Make sure to budget time for QA and non-feature work, like bugs and engineering health.
- Don't let the team have a fuzzy view of what's in the sprint. Nail it down, and don't focus on moving fast that you forget to make sure everyone's moving in the same direction.
- Also, don't take a large amount of unknown or high-risk work. Break down stories that are large or have a high uncertainity, and don't be afraid to leave some of that work for the next sprint.
- If you hear concerns from the team, wheather it's about velocity, low-certainty work, or work they think is bigger than what they estimated, don't ignore it. Address the issue, and recalibrate when necessary.

## Optimize your sprints with automation
Three most common automation rules used for sprints in Jira.
- Send a weekly Slack message with all issues open in the sprint.
- When a sprint finishes, then assign outstanding issues to the next sprint.
- When an issue moves 'In-Progress' and the issue's sprint field is empty, then move the issue to the active sprint.

Jira automation template library 
<https://www.atlassian.com/software/jira/automation-template-library#/>


