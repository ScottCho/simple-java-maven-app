pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        sh 'pwd'
      }
    }
    stage('script') {
      steps {
        sh 'sh \'ls /tmp\''
      }
    }
  }
}