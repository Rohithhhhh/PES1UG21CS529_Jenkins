pipeline {
    agent any
    stages {
//          stage('Clone repository') {
//              steps {
//                  checkout ([Sclass: 'GitSCM',
//                    branches: [[name:*/main']],
//                    userRemoteConfigs: [[url: 'https://github.com/Rohithhhhh/PES1UG21CS529_Jenkins/']]])
//              }
//          }
          stage('Build') {
              steps {
                  build 'PES2UG19CS529-1'
                  sh g++ main. cpp -o output'
              }
        }
        stage('Test') {
            steps {
                sh './output'
            }
        }
        stage ('Deploy') {
            steps {
                echo 'deploy'
            }
        }
    ｝
    post{
        failure{
            error 'Pipeline failed'
        }
    }
｝
