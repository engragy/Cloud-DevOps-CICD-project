# Project Solution Screenshots

[**URL01** - public GitHub repository for udapeople project](https://github.com/engragy/Cloud-DevOps-CICD-project/tree/master/)

[**URL02** - functioning front-end application in S3](http://udapeople-cfc642b.s3-website-us-east-1.amazonaws.com)

[**URL03** - functioning front-end application in cloudfront](http://dkpgtz0xple6z.cloudfront.net)

[**URL04** - healthy back-end application](http://54.224.146.136:3030/api/status)

[**URL05** - Evidence of Prometheus Server](http://44.204.35.8:9090) 

***
#### 1. Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.

- A public git repository with your project code. [URL01](https://github.com/engragy/Cloud-DevOps-CICD-project/tree/master/)
- Console output of various pre-deploy job failure scenarios:
	- **[SCREENSHOT01]** Build Jobs that failed because of compile errors. 
		![SCREENSHOT01](SCREENSHOT01.png)

	- **[SCREENSHOT02]**  Failed unit tests. 
		![SCREENSHOT02](SCREENSHOT02.png)

	- **[SCREENSHOT03]** Failure because of vulnerable packages. 
		![SCREENSHOT03](SCREENSHOT03.png)
	
	- **[SCREENSHOT04]** An alert from one of your failed builds.
		- Slack notification ![SCREENSHOT04](SCREENSHOT04 - Slack notification.png)
		- Email notification ![SCREENSHOT04](SCREENSHOT04 - Email notification.png)

***
#### 2. Utilize a Configuration Management Tool to Accomplish Deployment to Cloud-Based Servers

- **[SCREENSHOT05]** Console output of appropriate failure for infrastructure creation job (using CloudFormation). 
	![SCREENSHOT05](SCREENSHOT05.png)
- **[SCREENSHOT06]** Console output of a smoke test job that is failing appropriately. 
	![SCREENSHOT06](SCREENSHOT06.png)
- **[SCREENSHOT07]** Console output of a successful rollback after a failed smoke test. 
	![SCREENSHOT07](SCREENSHOT07.png)
- **[SCREENSHOT08]** Console output of successful promotion of new version to production in CloudFront. 
	![SCREENSHOT08](SCREENSHOT08.png)

- **[SCREENSHOT09]** Console output of successful cleanup job that removes old S3 bucket and EC2 instance. 
	![SCREENSHOT09](SCREENSHOT09.png)

- **[SCREENSHOT010]** Evidence that deploy jobs only happen on master branch. 
	![SCREENSHOT10](SCREENSHOT10.png)

- Evidence of deployed and functioning front-end application 
	- in an S3 bucket [URL02](http://udapeople-cfc642b.s3-website-us-east-1.amazonaws.com) 
	- in CloudFront. [URL03](http://dkpgtz0xple6z.cloudfront.net)
		![URL03_SCREENSHOT](URL03_SCREENSHOT.png)

- **[URL04_SCREENSHOT]** Evidence of healthy back-end application. [URL04](http://54.224.146.136:3030/api/status) 
	![URL04](URL04_SCREENSHOT.png)

***
### Surface critical server errors for diagnosis using centralized logging.

- **[URL05_SCREENSHOT]** Evidence of Prometheus Server. [URL05](http://44.204.35.8:9090)
	![URL05](URL05_SCREENSHOT.png)

- **[SCREENSHOT11]** Evidence that Prometheus is monitoring EC2 instances
	- memory 
		![SCREENSHOT11](SCREENSHOT11 - Free memory.png)
	- cpu usage 
		![SCREENSHOT11](SCREENSHOT11 - CPU usage.png)
	- disk usage of 
		![SCREENSHOT11](SCREENSHOT11 - Disk usage.png)

- **[SCREENSHOT12]** Evidence that Prometheus and AlertManager send alerts when certain conditions exist in the EC2 instance. ![SCREENSHOT12](SCREENSHOT12.png)




