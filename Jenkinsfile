pipeline {
  agent {
    node {
      label 'work2'
    }

  }
  stages {
    stage('docker') {
      steps {
        echo 'Start check cron'
        sh 'ironfish accounts:balance'
      }
    }

  }
}