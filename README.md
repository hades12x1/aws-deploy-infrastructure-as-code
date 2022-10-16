# aws-deploy-infrastructure-as-code

	- Suppose company is creating an Instagram clone like application. Developers pushed the latest version of their code in a index.html file located in a public S3 Bucket. Now the task is to deploy the application, along with the necessary supporting software into its matching infrastructure. This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

# Project setup: 
	1. Run stack network.yml (./Cloudformation/network.yml)
	2. Run stack server.yml  (./Cloudformation/server.yml)

![Screenshot](infrastructure-diagram.png)