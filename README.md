# Improving Open Source Security with Anchore & Snyk

Open source software components and dependencies are increasingly making up a vast majority of software applications. Along with the increased usage of OSS comes the inherent security risks these packages present. Enterprises looking to adopt a greater open source footprint should also employ effective tooling and processes to identify, manage, and mitigate the potential risks these libraries impose. 

Containers have been gaining popularity as well among enterprises. Uniquely allowing for development and packaging of applications, and their dependencies, to improve consistency and speed of production deployments. By nature of consistency, the quality of development and software releases also improves. 

Recognizing that container images need an added layer of security, Anchore conducts a deep image inspection and analysis to uncover what is within the image and generate a detailed manifest including packages, configuration files, and language modules and artifacts. Following analysis, user-defined acceptance policies are evaluated against the analyzed data to certify the container image. 

Due to an increased number of Anchore customers asking for high quality vulnerability data for OSS packages, Anchore has partnered with Snyk. Anchore Enterprise customers now have access to third-party vulnerability data for non-OS open source libraries from [Snyk's Vulnerability Database](https://snyk.io). This database is maintained by Snyk's security team, who spend a significant amount of time curating vulnerability data, as well as conducting their own research to uncover previously unknown vulnerabilities. Most of the vulnerabilities in Snyk's database originate from constant monitoring of other vulnerability databases, CVEs from NVD, monitoring user activity on Github, and both manual and bulk security research. Anchore Enterprise users will get updates to this vulnerability feed data at the interval they configure (default is six hours). In addition, Anchore policies can be created to enforce container images that include vulnerable packages from making their way into production environments.

Below is a snapshot of Anchore Enterprise with vulnerable Python packages identified by Snyk: 

Given that more organizations are increasing their use of both containers and OSS components, it is becoming more critical for enterprises to have the proper mechanisms in place to uncover and fix vulnerable packages within container images as early as possible in the development lifecycle. Anchore strongly recommends adding image scanning as part of a continous integration pipeline, and invoking Anchore policies to govern security vulnerabilities, configuration file contents, secrets, exposed ports, or any other user-defined checks. Find our more about Anchore Enteprise and Snyk here: [Anchore Enterprise](https://anchore.com/enterprise).