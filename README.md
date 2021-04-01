# CPE-695-Project

## Workflow
s
1. Release code is in main branch, **do not** use this branch for development 
2. Create branches from develop branch using this format: feature/<branch-name><ticket-number>
     - If we run into bugs or think of ideas for new features in the model, create a ticket in github with a description 
     - Example ticket -  Ticket #1 - First Commit Description: First commit in develop branch 
     - E.g  ```git checkout -b feature/firstCommit1```
3. Merge develop branch into your feature branch before pushing changes 
     - ```git checkout develop```
     - ```git pull develop```
     - ```git switch feature/<branch-name>```
     - ```git merge develop```
4. When branch is fully tested, submit merge request on GitHub into develop branch
5. When develop branch is good to go, submit merge request to main branch 
