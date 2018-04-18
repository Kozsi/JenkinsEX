pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            waitUntil() {
              echo 'Echo hello WOrld'
            }

          }
        }
        stage('not error') {
          steps {
            sleep 5
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