pipeline {
  agent {
    node {
      label 'Stability'
    }
    
  }
  stages {
    stage('Test') {
      steps {
        echo 'IE Test'
      }
    }
  }
  environment {
    IE = '9'
    Safari = '7'
  }
}