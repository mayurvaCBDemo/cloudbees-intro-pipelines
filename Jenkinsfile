pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('say hello') {
      steps {
        echo 'Hello World!'
        sh 'java -version'
      }
    }
  }
}