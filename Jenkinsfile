pipeline {
  agent {
    docker {
      image 'python:alpine'
    }

  }
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo 'lo'
          }
        }
        stage('test') {
          steps {
            echo '"we landed"'
          }
        }
      }
    }
  }
}