pipeline {
  agent {
    label 'jdk8'
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