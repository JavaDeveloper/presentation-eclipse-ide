1). Presentation slides - php/index.html

2). To launch presentation on the OpenShift PAAS you can perform following steps:
- Create OpenShift account
- Create presentation from current one:  rhc app create presentation php-5.3 --from-code=https://github.com/JavaDeveloper/presentation-eclipse-ide.git
- Commit and push to your OpneShift instance

Or you can follow these instractions to create presentation based on original project
- https://openshift.redhat.com/community/blogs/goodbye-powerpoint-hello-revealjs
