pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
  }
  stages {
    stage('Build') {
      steps {
        echo 'what was this step'
      }
    }
    stage('Shared Lib') {
      steps {
        helloWorld("Jenkins")
      }
    }
  }
}
