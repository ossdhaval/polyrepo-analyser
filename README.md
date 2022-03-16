# polyrepo-analyser
Analyse data across multiple repositories

## Modules

- Settings analysis (phase-1)
  - Need to know if all the selected repositories have same branch protection rules. If they are different, what is the differece. 
  - Need to know if all the selected repositories have same webhooks. If they are different, what is the differece. 
  - Need to know if any repository has created and managing a repo level secret. 
- Issue analysis (phase-1)
  - is that any `priority-1` labeled issue which is open since more than x days
- PR analysis (phase-1)
  - Is that any PR where there is no activity since x days
  - Is there any PR which is not merged since x days
- Label consistency 
  - are all labels, their description and color same across all repos
- User activity analysis
  - Users committing big chunks of code
  - Users who are reviewers but not reviewing PR for long time
  - Users with maximum PR review backlog
- Branches
  - List stale branches across all repositories

## Users

- Github organization manager 
- Github organization team member (phase-1)

## Phase-2
- ability to update and delete 
- org manager role that can update and delete



