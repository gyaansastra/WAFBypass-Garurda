<p align="center">
  <a href="https://debarghaya.blogspot.com/" target="_blank" rel="noreferrer"><img src="https://github.com/gyaansastra/gyaansastra/blob/main/images/banner.png" alt="my banner"></a>
</p>

# Garurda WAF Obfuscation Library

Survival can lead to innovation. Garurda's WAF library's inception is no exception. With the current surge of Log4Shell, we felt the pain and absence of any library for WAF obfuscation which can act as catalyst to evealuate the efficacy of WAF solutions. All the major vendors today does offer WAF solution's and they are undoubtedly good. But rather than getting than blindly trust these solutions and greeted by panic attack from the attacker it absolutely make sense to eveluate these WAF solutions as proactive measure to reduce risk. Garurda WAF Obfuscation is a python library developed to fast track the efficacy testing of Web Application Firewall. Individual fuctions can be used as rules in order to test specific modules during assesment. Currently Log4Shell obfuscation rules added and can be cosumed as library in any existing python project.


## Authors

- [Debarghaya Dasgupta](https://github.com/gyaansastra)
- [Kumar Harsh](mailto:harsh6100@gmail.com)


## Badges

![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&color=F7DF1E)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
## Acknowledgements

 - [Possible first publication of lower/upper bypass](https://twitter.com/stereotype32/status/1469313856229228544)
 - [HTML URL Encoding Reference](https://www.w3schools.com/tags/ref_urlencode.ASP)
 - [Bypassing NGFW/WAFs using data format obfuscations](https://d0znpp.medium.com/bypassing-ngfw-wafs-using-data-format-obfuscations-188351ea9e73)
 - [Apache Log4j 2 v. 2.15.0 - User's Guide](https://logging.apache.org/log4j/2.x/log4j-users-guide.pdf)
 - [GitHub Reviewed CVE-2021-44228 - Remote code injection in Log4j](https://github.com/advisories/GHSA-jfh8-c2jp-5v3q)
 - [LOG4J2-3230 Certain strings can cause infinite recursion](https://issues.apache.org/jira/browse/LOG4J2-3230)
 - [Awesome list of secrets in environment variables](https://github.com/Puliczek/awesome-list-of-secrets-in-environment-variables)
 - [Exploiting CVE-2021-44228 using PDFs as delivery channel - PoC](https://github.com/eelyvy/log4jshell-pdf)
 - [Kozmer Log4Shell POC](https://github.com/kozmer/log4j-shell-poc)
 - [Lunasec](https://github.com/christophetd/log4shell-vulnerable-app)
 


## Deployment
pip install waf-bypass-rules-garuda

```shell 
Import Library and Specific Function (e.g. from WAFBypass.wafbypass import log4jRules) 
```
## Features

- Log4Shell WAF Obfuscation
- Cross platform

## 🚀 About Us
We are bunch of passionate people who want to contribute to the community. We have learned from the community and hence felt its our moral responsibility to contribute.

## Feedback

If you have any feedback, please reach out to us at gyaansastra@gmail.com


## 🤝 Connect with me:
[![Blogspot](https://img.shields.io/badge/Blogger-000?style=for-the-badge&logo=blogger&logoColor=white)](https://debarghaya.blogspot.com/)
[![Github](https://img.shields.io/badge/Github-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gyaansastra)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/debarghaya/)


## Roadmap

- Multi-Vendor WAF Support
- Performance Optimization

