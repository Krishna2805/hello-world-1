pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }

    stage('Build') {
      agent any
      steps {
        echo 'Building Hello World Project'
        echo 'Hello world'
      }
    }

  }
}