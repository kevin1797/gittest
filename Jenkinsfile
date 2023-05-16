pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sleep 10
            echo 'hello'
          }
        }

        stage('') {
          steps {
            echo 'world'
          }
        }

      }
    }

  }
}