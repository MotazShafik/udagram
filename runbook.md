# Check the health of of the EB environment  
1. Start by connecting the EB CLI to the environment with **eb use udagram-dev**.
2. Check the health of the environment with the **eb health**. This will bring up a table with different information about the servers running your application.
3.If you see that the health is not indicating an "OK" status, use the **eb logs** command. This will print out the logs to your terminal. You can inspect them to look for failures.
---
# Operations of the deployment process

1. We are using Circle CI for CI/CD , create a free account and link it to repo contains the project 

2. modify the application and make sure it is working in you local machine 
3. **git init** to initiate git in the main folder then **git add .** then **git commit -m "first commit"** then **git remote [the repo link]** then **git push** to the repo 
4. once you push your code and you already setup the porject in circleCi correctly you will find that Circle Ci automatically activate the workflow.

. Those runbooks will serve as a way to communicate with future developers and anybody involved in diagnosing outages of the Full-Stack application.