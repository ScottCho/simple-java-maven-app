pipeline {
  agent any
  stages {
    stage('') {
      steps {
        withAnt() {
          withAnt(installation: 'init')
        }

      }
    }
    stage('script') {
      steps {
        sh 'sh \'ls /tmp\''
      }
    }
  }
}