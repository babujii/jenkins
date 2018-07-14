pipeline {
  agent any
  stages {
    stage('build stage') {
      parallel {
        stage('build stage') {
          steps {
            sh 'uptime'
          }
        }
        stage('') {
          steps {
            echo 'build'
          }
        }
      }
    }
    stage('test stage') {
      parallel {
        stage('test stage') {
          steps {
            sh '''uptime
date'''
          }
        }
        stage('') {
          steps {
            echo 'test'
          }
        }
      }
    }
    stage('Deploy stage') {
      parallel {
        stage('Deploy stage') {
          steps {
            sh '''uptime
date
uname -a'''
          }
        }
        stage('') {
          steps {
            echo 'Deploy'
          }
        }
      }
    }
  }
}