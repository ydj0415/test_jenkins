pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        echo 'start'
      }
    }

    stage('job 001') {
      parallel {
        stage('job 001') {
          steps {
            sh 'echo "job 001"'
          }
        }

        stage('job 002') {
          steps {
            sh 'echo "job 002"'
          }
        }

      }
    }

    stage('end') {
      steps {
        echo 'end'
      }
    }

  }
}