# Refactor Udagram App into Microservices and Deploy

Microservices containerized and deployed on a Kubernetes cluster.

### Dependencies
* Cloud Services
    * Amazon Web Services S3 - Resource hosting and deployments
    * AWS CloudFront - CDN for SPA
    * AWS EKS - Backend API
    * AWS DynamoDB - Persistent Datastore
    * AWS Cognito - User Authentication
* Performance Tracking and DevOps Tools:
    * AWS CloudWatch - Performance and Health checks
    * Sentry - Bug Reporting
    * Travis (CI/CD)
* Frameworks:
    * Ionic (Javascript) (Frontend)
    * Node.js (Javascript) (Backend)