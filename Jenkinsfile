library(
  identifier: 'hello-shared-library@master',
  retriever: modernSCM([
    $class: 'GitSCMSource',
    remote: 'git@github.com:RobeDevOps/hello-shared-library.git',
    credentialsId: 'github-creds'
  ])
) _

pipeline {
    agent any
    stages{
        stage("Hello"){
            steps{
                hello name: "roberto"
            }
        }
    }
}