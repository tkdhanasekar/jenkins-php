pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'php --version'
      }
    }
    stage('hello') {
      steps {
        sh 'php hello.php'
      }
    }
  }
}
