pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            sh 'echo "hallo van development"'
          }
        }

        stage('nondev') {
          steps {
            echo 'nondev'
          }
        }

      }
    }

  }
}