pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh './addition.sh'
      }
    }
  }
  environment {
    N1 = '10'
    N2 = '20'
  }
}