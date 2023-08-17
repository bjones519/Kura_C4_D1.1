Deployment 1.1
---

### Jenkins Pipeline
1. Was able to Login to Jenkins server and setup the pipeline
2. Ran the build and the pipeline was successful with no issues

### Elastic Beanstalk Deployment
1. Zipped python files and uploaded them to Elastic Beanstalk
2. Deployed the deployment to elastic beanstalk and saw a degraded health status
3. Requested and downloaded the logs
4. In the logs I found this error "ModuleNotFoundError: No module named 'application'"
5. That error occurs due to flask not knowing where to look for resources such as templates and static files
6. I changed the file named `app.py` to `application.py`, rezipped the files and deployed to Elastic Beanstalk and the Health status was ok



