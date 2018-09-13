pipeline {
  agent any
  stages {
    stage('init') {
      steps {
        sh 'ls /tmp'
      }
    }
    stage('script') {
      steps {
        sh 'sh \'ls /tmp\''
      }
    }
  }
}