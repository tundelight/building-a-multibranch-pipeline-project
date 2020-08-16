pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello world!"'
      }
    }

    stage('Test') {
      steps {
        sh 'echo test'
      }
    }

    stage('Deliver for development') {
      steps {
        sh 'echo develop'
      }
    }

  }
}