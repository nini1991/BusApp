pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('test') {
      steps {
        echo 'test'
      }
    }
  }
  environment {
    test = '1'
  }
}