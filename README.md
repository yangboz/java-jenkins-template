# java-jenkins-template
Template for Jenkins jobs for Java projects. 

# Mvn life-cycle

    mvn -f pom.xml -Dspring.profiles.active=dev -U checkstyle:checkstyle pmd:cpd pmd:pmd findbugs:findbugs jxr:jxr javancss:report jdepend:generate taglist:taglist surefire-report:report cobertura:cobertura

# Overview

![Screenshot of "JenkinsJavaOverview"](https://raw.githubusercontent.com/yangboz/java-jenkins-template/master/Jenkin-Java-overview.png)

