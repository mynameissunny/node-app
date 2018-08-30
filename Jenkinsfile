pipeline {
  agent {
    docker {
      image 'goforgold/build-container:latest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'goforgold/build-container:latest'
      }
    }
  }
}