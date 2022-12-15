# Udagram Project
## Deploy a high-availability web app using CloudFormation - Udagram Project

### Problem Statement 
* Your company is creating an Instagram clone called Udagram. Developers want to deploy thier application to the AWS infrastructure. They pushed thier latest contribution to a public S3 Bucket.  

* You have been tasked with provisioning the required infrastructure and deploying thier latest contribution files which are located in a public S3 Bucket to the Apache Web Server running on an EC2 instance, along with the necessary supporting software.

* This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

How to run it ?
-------------------
  you can run the part as followed :
  ```
    ./create.sh [stackName1] network.yml network-para.json
    ./create.sh [stackName2] server.yml server-para.json
  ```

How to test that it works
----------------------------
Here is the url for testing
```
http://serve-webap-1fjdw54dynden-1770811822.us-east-1.elb.amazonaws.com/?C=M;O=A 
```