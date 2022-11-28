pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('mm') {
      steps {
        sh 'python3 main.py'
      }
    }
  }
}