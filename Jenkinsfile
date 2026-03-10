pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo "Compiling Application..."'
      }
    }
    stage('Unit Tests') {
      steps {
        bat 'echo "Running Unit Tests 1-10..." && timeout 5'
      }
    }
    stage('Deploy') {
      steps {
        bat 'echo "Deploying to Production Server..."'
      }
    }
  }
}