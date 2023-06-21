
## Jenkins Pipeline Shared Libraries

A shared library in Jenkins is a collection of Groovy scripts shared between different Jenkins jobs. To run the scripts, they are pulled into a Jenkinsfile. Each shared library requires users to define a name and a method of retrieving source code.

# Installation

These shared libraries may be accessed one of three ways:

  1. Add this repo to 'Global Pipeline Libraries' in the Jenkins UI.
  2. Include a libraries block in declarative pipeline syntax.
  3. Include this library in an @Library statement in a Pipeline script.

# Global Pipeline Libraries

Refer this link https://jenkins.io/doc/book/pipeline/shared-libraries/#global-shared-libraries about adding shared libraries via the Jenkins UI.

