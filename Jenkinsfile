pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello this is build Job'
        sh 'mkdir jenkins'
      }
    }
    stage('Test') {
      steps {
        echo 'This is test'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy stage'
      }
    }
  }
}