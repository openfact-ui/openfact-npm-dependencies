#!/usr/bin/groovy
@Library('github.com/fabric8io/fabric8-pipeline-library@master')
def dummy
clientsNode {
  ws {
    checkout scm
      npmUpdateOrganisationDependencies{
        organisation = 'openfact-ui'
      }
  }
}
