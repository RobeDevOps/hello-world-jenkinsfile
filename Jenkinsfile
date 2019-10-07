library(
  identifier: 'hello-shared-library@master',
  retriever: modernSCM([
    $class: 'GitSCMSource',
    remote: 'https://github.com/RobeDevOps/hello-shared-library.git'
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