pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'hello'
          }
        }

        stage('error') {
          steps {
            echo 'world'
          }
        }

      }
    }

  }
}