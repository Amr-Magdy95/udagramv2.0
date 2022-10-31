# Infrastructure Description

This is a brief description of the high-level over of the project.

## Infrastructure Diagram
(./images/HighLevelDiagram.jpg)

## Infrastructure macro-description
- RDS
  - Provision of a PostgreSQL database.
- S3
  - Provides a bucket for the backend web server hosted on eb.
  - Provides Static web hosting for the frontend
- Elastic Beanstalk
 - Provides web server hosting for our NodeJS application


