pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh '''npm i
'''
      }
    }
    stage('Build') {
      steps {
        sh 'npm run build'
      }
    }
  }
}