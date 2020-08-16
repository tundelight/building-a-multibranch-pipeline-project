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
        sh 'echo deliver for development'
      }
    }

    stage('Deploy for production') {
      steps {
        timeout(activity: true, unit: 'MINUTES', time: 20) {
          echo 'ok'
        }

      }
    }

  }
}