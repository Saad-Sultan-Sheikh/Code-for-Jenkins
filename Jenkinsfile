pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('Fibonacci') {
      steps {
        sh 'python3 fibonacci.py'
      }
    }
  }
}
