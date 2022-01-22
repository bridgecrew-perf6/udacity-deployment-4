# Continuous Integration/Delivery Process

- Pipeline is triggered by pushing a new code commitment to the GitHub repo
- GitHub triggers CircleCi to:

1. Create build environment
2. Prepare environment variables
3. Install Dependencies (NPM, AWS CLI v2)
4. Configure AWS and Elastic Beanstalk CLI
5. Install packages (frontend and backend)
6. Build Projects (frontend and backend)
7. Deploy applications (frontend and backend)
