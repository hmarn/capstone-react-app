[![CircleCI](https://dl.circleci.com/status-badge/img/gh/hmarn/capstone-react-app/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/hmarn/capstone-react-app/tree/main)

## Capstone - Cloud DevOps

### Instructions

- Working in AWS
- Using Jenkins or Circle CI to implement Continuous Integration and Continuous Deployment
- Building pipelines
- Working with Ansible and CloudFormation to deploy clusters
- Building Kubernetes clusters
- Building Docker containers in pipelines

### Project Tasks

Step 1: Propose and Scope the Project
- [x] ReactJS frontend application - Currency Exchange converter
- [x] Circle CI is used for Continuous Integration phase
- [x] Deployment type: Rolling deployment

Step 2: Use Jenkins or Circle CI, and implement blue/green or rolling deployment.
- [x] Using Circle CI, set up circle CI account and connected git repository.
- [x] Setting up environment to where application is going to deploy

Step 3: Pick AWS Kubernetes as a Service, or build your own Kubernetes cluster.
- [x] Using CloudFormation to build applicaiton “infrastructure”; i.e., the Kubernetes Cluster.
- [x] Created the EC2 instances
- [x] As a final step, the Kubernetes cluster is being initialized. The Kubernetes cluster initialization is done by Cloudformation using CircleCI orbs.

Step 4: Build your pipeline
- [x] Construct the pipeline in GitHub repository.
- [x] Set up all the steps that pipeline will include.
- [x] Configure a deployment pipeline.
- [x] Include the Dockerfile/source code in the Git repository.
- [x] Include with the Linting step both a failed Linting screenshot and a successful Linting screenshot to show the Linter working properly.

Step 5: Test your pipeline
- [x] Perform builds on the pipeline.
- [x] Verify that the pipeline works as you designed it.
- [x] Taking a screenshot of the Circle CI or Jenkins pipeline showing deployment, and a screenshot of your AWS EC2 page showing the modified (for rolling) instances.


### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon EKS](https://aws.amazon.com/) - https://aws.amazon.com/eks/
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Docker](https://www.docker.com/) - Docker Containerization
- [Kubernetes](https://kubernetes.io/) - Kubernetes Cluster 

