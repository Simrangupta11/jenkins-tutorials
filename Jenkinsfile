pipeline {
  agent any
  stages {
    stage('pre-build') {
      parallel {
        stage('pre-build') {
          steps {
            echo 'our build is running'
          }
        }

        stage('') {
          steps {
            echo 'our build is running'
          }
        }

      }
    }

    stage('test') {
      steps {
        catchError()
      }
    }

  }
}