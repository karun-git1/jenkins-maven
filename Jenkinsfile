pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo "Building the application..."
'''
      }
    }

    stage('test') {
      steps {
        sh '''echo "Running tests..."
'''
      }
    }

    stage('deploy') {
      steps {
        sh '''echo "Deploying the application..."
'''
      }
    }

  }
  environment {
    APP_ENV = 'production'
  }
}