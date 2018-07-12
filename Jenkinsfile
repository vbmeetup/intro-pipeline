pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('say hello') {
      steps {
        echo 'hi jenkins'
        sh 'java -version'
      }
    }
  }
}