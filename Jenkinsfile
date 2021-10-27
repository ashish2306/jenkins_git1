pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Ashish Kumar Gupta"'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            sh 'echo "gupta"'
          }
        }

        stage('Test_par') {
          steps {
            echo 'Gupta1'
          }
        }

      }
    }

    stage('Depl') {
      steps {
        echo 'done successfully'
      }
    }

  }
}