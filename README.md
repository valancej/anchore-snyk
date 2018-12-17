# Improving Open Source Security with Anchore & Snyk

Open source software components and dependencies are increasingly making up a vast majority of software applications. Along with the increased usage of OSS comes the inherent security risks these packages present. Enterprises looking to adopt a greater open source footprint should also employ effective tooling and processes to identify, manage, and mitigate the potential risks these libraries impose. 

Containers have been gaining popularity as well among enterprises. Uniquely allowing for development and packaging of applications, and their dependencies, to improve consistency and speed of production deployments. By nature of consistency, the quality of development and software releases also improves. 

Recognizing that container images need an added layer of security, Anchore conducts a deep image inspection and analysis to uncover what is within the image (packages, files, software artifacts). Following analysis, user-defined acceptance policies are evaluated against the analzyed data to certify the container images. 

Due to an increased number of Anchore customers asking for high quality vulnerability data for OSS packages, Anchore has partner with Snyk. Anchore Enteprise customers now have access to third-party vulnerability data for non-OS open source libraries from [Snyk](https://snyk.io). This database is maintained by Snyk's security team, who spend a significant amount of time curating vulnerability data, as well as conducting their own research to uncover previously unknown vunerabilities. Most of the vulnerabilities in Snyk's datavase originate from constant monitoring of other vulnerability databases, CVEs from NVD, monitoring user activity on Github, and both manual and bulk security research. 

Below is a snapshot of Anchore Enterprise with vulnerable Python packages identified by Snyk: 