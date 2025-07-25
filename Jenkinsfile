pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'building the code......'
      }
    }

    stage('test') {
      steps {
        echo 'testing the code.......'
      }
    }

    stage('deployment') {
      steps {
        echo 'deploying the code.....'
      }
    }

    stage('sending notification') {
      steps {
        echo 'notification sent........'
      }
    }

    stage('monitoring') {
      steps {
        echo 'monitoring the code by jk-v10 .........'
      }
    }

    stage('test1') {
      steps {
        sh '''date
'''
      }
    }

  }
}