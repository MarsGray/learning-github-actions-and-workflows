# Workflow predictions

1. What will cause this workflow to run?
    - workflow_dispatch is the event that will trigger the workflow to run
2. How many jobs will run?
    - I am assuming that only 1 job is going to run
3. What operating system will the job use?
    - It will use ubuntu 
4. How many steps are in the job?
    - There are 5 steps in the job
5. Which steps use `run:`?
    - The one that creates and displays the investigation file and the one that prints the environment information
6. Which steps use `uses:`?
    - The steps that uploads the investigation artifact and the one that checks out the repository
7. Where will `result.txt` initially be created?
    - It will be created in the investigation-output directory
8. What information do I expect to see inside `result.txt`?
    - A message saying that the workflow is completed, the run number, commit, and the branch
9. Will `result.txt` automatically appear in my Git repository?
    - It should automatically appear in my Git repository

10. What do I think an uploaded artifact will look like?
    - Like a regular degular file