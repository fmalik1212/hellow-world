pipeline {
  agent any
  stages {
    stage('Log Tool Version') {
      steps {
        sh '''mvn --version
git --version
java -version'''
      }
    }

    stage('testing') {
      steps {
        echo 'good'
      }
    }

  }
}