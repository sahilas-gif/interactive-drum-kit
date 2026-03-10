pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Compiling Application..."
'''
      }
    }

    stage('Unit Tests') {
      steps {
        sh 'echo "Running Unit Tests 1-10..." && timeout 5'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "Deploying to Production Server..."'
      }
    }

  }
}