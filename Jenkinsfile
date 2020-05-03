pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo \'build succesfulll\''
        sh 'mvn package'
      }
    }

    stage('Test') {
      steps {
        sh 'echo \'test succeded\''
      }
    }

  }
}