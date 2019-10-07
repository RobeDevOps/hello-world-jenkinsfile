// library(
//   identifier: 'hello-world@master',
//   retriever: modernSCM([
//     $class: 'GitSCMSource',
//     remote: 'git@bitbucket.org:ansiblerobedevops/hello-world.git',
//     credentialsId: 'rcidevops'
//   ])
// )

@Library('rcidevops/hello-world@master') _

pipeline {
    agent any
    stages{
        stage("Hello"){
            steps{
              echo "hello"
                // hello name: "roberto"
            }
        }
    }
}