pipeline {
  agent {
    docker {
      image 'python:latest'
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
            sh 'echo "we are here"'
          }
        }
      }
    }
  }
}