pipeline {
  agent any
  stages {
    stage('11') {
      steps {
        sh 'echo "hello world"'
        sh 'echo "nihao"'
      }
    }

    stage('22') {
      steps {
        cleanWs(cleanWhenSuccess: true)
      }
    }

  }
}