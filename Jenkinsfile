pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
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