# GITHUBACTIONS
================
**Topics:
 1. What is GitHub Actions
 2. How to use - Step by Step DEMO
 3. A demo workflow file - how to create, run and check results
 4. Terms : Workflows, Events, Jobs, Steps**
==============
#                 # GITHUB==WITHIN GITHUB FEATURE
CODING>>>BUILD>>>DEPLOY>>>TESTING>>RELEASE

# JENKINS==COMMON CI TOOL ==IT IS SOME EXTERNAL TOOL
JOB === BUILD ,DEPLOY,TEST,RELEASE.
# AUTOMATE SDLC workflows
# implemet CICD DevOps 

# 
# step 1
create account github
# step 2 
create a new repo
# step3
in the repo create a folder .github/workflows
# step 4
in the folder create a YAML file with .yml extension
eg demo.yaml

[referhere](https://gist.github.com/weibeld/f136048d0a82aacc063f42e684e3c494)

# github also contains some containers ===virtual machines ,ubuntu machines,linux 
# step 5
add the content of the workflow in the file
# step 6
commit and push the changes 
# step 7
Go to main page and click " Actions "
# step 8
select the workflows from left sidebar and check the logs  and results

re run job also possible
events ,status,branch,actions

# WORKFLOW : collection  of jobs ,defined in a YAML file
# name
Events: any activity in the repo that can trigger a workflow
# on 
# JOBS : collection os steps
# STEPS: Actions to be taken , commands ,scripts
steps:
Chain JObs -- :needs
=====================
![preview](githubactions1)
