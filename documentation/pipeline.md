# Pipeline

This is a brief description of the Pipeline of the project.

## Pipeline Diagram
(./images/PipelineDiagram.jpg)

## Steps of the Pipeline
- Build Step
  - Preparing the environment.
  - Installing Dependencies
    - `circleci/node@5.0.2`
    - `circleci/aws-elastic-beanstalk@2.0.1`
    - `circleci/aws-cli@3.1.1`
    - Configuring AWS keys and Environment Variables.
    - Installing Front-End and Back-End dependencies.
  - Building the Front-End and the Back-End.
- Approval Step for Deployment
- Deployment Step 




