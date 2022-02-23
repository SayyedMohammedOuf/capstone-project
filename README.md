# Capstone Project

**1- Circleci Pipeline:** https://app.circleci.com/pipelines/github/SayyedMohammedOuf/capstone-project/7/workflows/235b9fa2-c963-487f-aab1-d72bfaa7d1ef

**2- CI/CD Pipeline consists of:**

- Linting Step.
- Testing Step.
- Push Docker Container To Dockerhub Repo Step.
- Create EKS Cluster Step
- Deploy App To EKS Cluster Step. [using rolling deployment]

###Notes:
- I can't access aws console!!
- I've an issue in the last step, kindly check this link:
 [The connection to the server localhost:8080 was refused - did you specify the right host or port?
]
https://app.circleci.com/pipelines/github/SayyedMohammedOuf/capstone-project/50/workflows/c1d16ef6-94a1-4e3a-943e-2425a7597e52/jobs/69

- Also I've added a screenshot of the deploying the cluster to EKS in the screenshots folder.

#### I have posted the issues I have in the knowledge center but I did not get any help, please check the following links for more details about the issue I have now:

- https://knowledge.udacity.com/questions/799821
- https://knowledge.udacity.com/questions/798559