pipeline {
  agent any
  stages {
    stage('begin job') {
      steps {
        build(job: 'test', quietPeriod: 10, wait: true)
      }
    }

    stage('job step 1') {
      steps {
        echo 'job step 1 start'
        sleep 5
      }
    }

    stage('end job') {
      steps {
        echo 'end job'
      }
    }

  }
}