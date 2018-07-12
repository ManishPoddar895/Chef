pipeline {
  agent {
    docker {
      image 'nginix'
      args '-p 80:80'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        echo 'Hello this is build Job'
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