This example demonstrates how to use the BuildWrapper to analyze a C++ project with the SonarQube Scanner on Mac OSX

Prerequisites
=============
* G++ compiler to compile the project sample
* [SonarQube](http://www.sonarqube.org/downloads/) 6.7+
* [SonarQube Scanner](https://redirect.sonarsource.com/doc/install-configure-scanner.html) 2.8+
* [SonarCFamily for C/C++](https://www.sonarsource.com/why-us/products/codeanalyzers/sonarcfamilyforcpp.html)
* [SonarSource Build Wrapper](https://docs.sonarqube.org/pages/viewpage.action?pageId=7996665docs)

Usage
=====
* Run the build wrapper:

        alias bw='/opt/build-wrapper-macosx-x86/build-wrapper-macosx-x86'
        bw --out-dir bw-outputs ./build.sh

* Analyze the project with SonarQube using the SonarQube Scanner:

        sonar-scanner
