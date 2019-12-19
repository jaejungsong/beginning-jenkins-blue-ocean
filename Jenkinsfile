pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean compile'
      }
    }

    stage('Unit Test') {
      steps {
        sh 'echo "Unit Test"'
      }
    }

    stage('Publish') {
      steps {
        sh 'echo "publish"'
      }
    }

  }
}