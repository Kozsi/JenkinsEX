pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello World'
          }
        }
        stage('') {
          steps {
            waitUntil()
            echo 'Siker'
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        echo 'Hello Deploy'
      }
    }
  }
}