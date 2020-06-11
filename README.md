# demo-jenkins-javaapp

This repository is copied from https://github.com/hgautam/maven-examples.git for learning Jenkins

Project: java-demo-app

Tasks:
1. Clone java-demo-app in your repo
2. Import in Jenkins project. Check details on edx platform for the free course: LinuxFoundationX: LFS167x
Introduction to Jenkins
3. Build and Test as mentioned here: https://courses.edx.org/courses/course-v1:LinuxFoundationX+LFS167x+2T2020/courseware/fa133ee76d9243f2a32acccafb580430/62b3f1946656467abc7d1b6e00fe618e/4?activate_block_id=block-v1%3ALinuxFoundationX%2BLFS167x%2B2T2020%2Btype%40vertical%2Bblock%40c9b9a0706db04a4d94cb647d9354d7b2

Install Java 8 and set JAVA_HOME before starting the project.

Jenkins Plugins installed:
1. https://plugins.jenkins.io/build-environment/ to set build environment variables.
2. https://plugins.jenkins.io/github-pullrequest/ to get project directly from GitHub and set the credentials while configuring job in jenkins.
3. https://plugins.jenkins.io/jacoco/ for code coverage reports.
4. https://plugins.jenkins.io/maven-plugin/ for maven integration.
5. https://plugins.jenkins.io/warnings-ng/ - visualisation for warnings, compiler errors, etc.
