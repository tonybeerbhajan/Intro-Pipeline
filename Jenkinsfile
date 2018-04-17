pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello Charlotte'
        sh 'java -version'
      }
    }
  }
}