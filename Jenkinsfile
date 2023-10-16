pipeline {
  agent any
  stages {
    stage('Version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('Build and Run') {
      steps {
        sh 'python3 fibonacci.py'
      }
    }
  }
}
