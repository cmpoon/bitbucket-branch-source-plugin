bitbucket-branch-source-plugin (CMPoon v1.6.1)
------------------------
Bitbucket Branch Source Plugin allows use of Bitbucket Cloud and Server as a multi-branch project source in two different ways:

- *Single repository source*: automatic creation of jobs for branches and pull requests in a specific repository.
- *Team/Project folders*: automatic creation of multi-branch projects for each visible repository in a specific Bitbucket Team or Project.

_Updated to respect Jenkins No-Proxy configuration_

## Configuration 

See the user guide at https://go.cloudbees.com/docs/cloudbees-documentation/cje-user-guide/chapter-bitbucket.html

## Building and Installing

This plugin is built with maven with the following command:
    
    mvn package

This will generate a target/junit.hpi plugin container, which can be installed directly to Jenkins via Manage Jenkins -> Manage Plugins -> Advanced -> Upload Plugin.


Based on [Jenkins plugin dev guide](https://wiki.jenkins-ci.org/display/JENKINS/Plugin+tutorial)