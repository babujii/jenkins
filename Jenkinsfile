pipeline {
  agent any
  stages {
    stage('build stage') {
      steps {
        sh 'uptime'
      }
    }
    stage('test stage') {
      steps {
        sh '''uptime
date'''
      }
    }
    stage('Deploy stage') {
      steps {
        sh '''uptime
date
uname -a'''
      }
    }
  }
}